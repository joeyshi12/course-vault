---
---

```SQL
SELECT A2 ... An
FROM R1 ... Rm
WHERE condition
```

## IN / NOT IN
```SQL
SELECT M.StarID, M.Name
FROM MovieStar M
WHERE M.Gender = 'female' AND
      M.StarID IN (SELECT S.StarID
                   FROM StarsIn S
                   WHERE MovieID = 28)
```