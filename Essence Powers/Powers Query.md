```dataview
TABLE slot,
  rows.file.link AS Powers,
  length(rows) AS Power_Count
FROM "Essence Powers"
WHERE any(essences, (e) => e = "Lightning")
WHERE typeof(essences) = "array"
GROUP BY slot
SORT slot
```
