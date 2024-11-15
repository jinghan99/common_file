删除sql protein_g 字段 中的g
```sql
UPDATE food_nutrition
SET protein_g = REPLACE(protein_g, 'g', '')
WHERE protein_g LIKE '%g';

```
