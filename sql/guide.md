Example Style Guide 

### Aliasing
- Should always be full words related to the source 
- Always include the AS keyword
- Applies to both column and table names

#### Do

```sql
SELECT
  date(timestamp) AS day
FROM
  modelled.data AS data
LIMIT
  100
```

#### Avoid
```sql
SELECT
  date(timestamp) dat
FROM
  modelled.data dt
LIMIT
  100
```
