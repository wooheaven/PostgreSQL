[ regexp_split_to_table on PostgreSQL]

PostgreSQL9.3 Document https://www.postgresql.org/docs/9.3/static/functions-string.html

```{sql}
mydatabase=> -- regexp capturing group and Negative-Lookahead
mydatabase=> SELECT  regexp_split_to_table( 'a1=1,2;B2b=2,3,4;C3c={3,4,5;4,5,6};D4d={4,5,6;7,8,9}', '(;(?![0-9]))');
 regexp_split_to_table 
-----------------------
 a1=1,2
 B2b=2,3,4
 C3c={3,4,5;4,5,6}
 D4d={4,5,6;7,8,9}
(4 rows)

mydatabase=> -- regexp capturing group and Positive-Lookahead
mydatabase=> SELECT  regexp_split_to_table( 'a1=1,2;B2b=2,3,4;C3c={3,4,5;4,5,6};D4d={4,5,6;7,8,9}', '(;(?=[A-Z]))');
 regexp_split_to_table 
-----------------------
 a1=1,2
 B2b=2,3,4
 C3c={3,4,5;4,5,6}
 D4d={4,5,6;7,8,9}
(4 rows)
``` 
