# SQL snippets

Convert array string into array of integers (or something else)

```sql
SELECT ARRAY(
   SELECT CAST(integer_element AS INT64)
   FROM UNNEST(
     JSON_EXTRACT_ARRAY(source_field,'$')
   ) AS integer_element
 ) AS integer_array
FROM source_table
```

Get max/min value of array

```sql
SELECT 
   <COLUMN1>...<COLUMNN>,
   MIN(value)
FROM
   <TABLE>
CROSS JOIN UNNEST(<ARRAY_COLUMN>) as value,
group by <COLUMN1>...<COLUMNN>
```

To use a subset of a table and process less data use (BigQuery)

```jsx
TABLESAMPLE SYSTEM (integer PERCENT)
```