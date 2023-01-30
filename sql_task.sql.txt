SELECT tb1.column_1,
       tb1.column_2,
       tb1.column_3,
       tb2.email 
FROM splendid-watch-376217.table1.table_1 AS tb1
INNER JOIN splendid-watch-376217.table1.table_2 AS tb2 ON tb1.join_id=tb2.join_id
WHERE (tb1.column_1/2 - FLOOR(tb1.column_1/2)) = 0
  AND tb1.column_2 < tb1.column_1
  AND CAST(tb1.column_3 AS STRING) LIKE '%1'