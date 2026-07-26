```dataview
TABLE slot,
  rows.file.link AS Powers,
  length(rows) AS Power_Count
FROM "Essence Powers"
WHERE typeof(essences) = "array"
WHERE any(essences, (e) => e = "Oath")
GROUP BY slot
SORT slot
```