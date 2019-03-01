# Install and Run PostgreSQL
&ensp;[Install PostgreSQL9.3.6 : on docker](01_Install_and_Run_PostgreSQL/01_Install_PostgreSQL9.3.6_on_docker.md)  
&ensp;[Run PostgreSQL9.3.6 : on docker](01_Install_and_Run_PostgreSQL/02_Run_PostgreSQL9.3.6_on_docker.md)

# Documents
[PostgreSQL current Documentation](https://www.postgresql.org/docs/current/static/index.html)  
Table of Contents  
╠═II. [The SQL Language](https://www.postgresql.org/docs/current/static/sql.html)  
║&ensp;╠═7. [Queries](https://www.postgresql.org/docs/current/static/queries.html)  
║&ensp;║&ensp;╠═7.2. [Table Expressions](https://www.postgresql.org/docs/10/static/queries-table-expressions.html)  
║&ensp;║&ensp;║&ensp;╚═7.2.1. [The FROM Clause](https://www.postgresql.org/docs/10/static/queries-table-expressions.html#QUERIES-FROM)    
║&ensp;║&ensp;║&ensp; &ensp; ╚═7.2.1.1. Joind Tables : [examples](02_Use_PostgreSQL/current/02_II/07/2/1/1/01_Joined_Tables_Examples.md)  
║&ensp;║&ensp;╚═7.8. [WITH Queries](https://www.postgresql.org/docs/current/static/queries-with.html)  
║&ensp;║&ensp; &ensp; ╚═7.8.1. [SELECT in WITH](https://www.postgresql.org/docs/current/static/queries-with.html#QUERIES-WITH-SELECT)    
║&ensp;║&ensp; &ensp; &ensp; &nbsp;╚═7.8.1.1. [find recursive path from row to row](02_Use_PostgreSQL/current/02_II/07/8/1/01_find_path_from_row_to_row.md)  
║&ensp;╠═8. [Data Types](https://www.postgresql.org/docs/current/static/datatype.html)  
║&ensp;║&ensp;╚═8.1. [Numeric Types](https://www.postgresql.org/docs/current/static/datatype-numeric.html)  
║&ensp;║&ensp; &ensp; ╚═8.1.4. [Serial Types](https://www.postgresql.org/docs/current/static/datatype-numeric.html#DATATYPE-SERIAL)    
║&ensp;║&ensp; &ensp; &ensp; &nbsp;╚═8.1.4.1. [add column id as SERIAL NOT NULL PRIMARY KEY](02_Use_PostgreSQL/current/02_II/08/01/4/01_add_column_as_serial_to_prevent_duplication.md)  
║&ensp;╚═9. [Functions and Operators](https://www.postgresql.org/docs/current/static/functions.html)  
║&ensp; &ensp; ╠═9.4. [String Functions and Operators](https://www.postgresql.org/docs/current/static/functions-string.html)  
║&ensp; &ensp; ║&ensp;╠═9.4.Table_9.8. SQL String Functions and Operators  
║&ensp; &ensp; ║&ensp;║&ensp;╚═9.4.Table_9.8.|| (String concatenation) : [example](02_Use_PostgreSQL/current/02_II/09/04/Table_9.8./01_string_concatenation.md)  
║&ensp; &ensp; ║&ensp;╚═9.4.Table_9.9. Other String Functions  
║&ensp; &ensp; ║&ensp; &ensp;&nbsp;╠═9.4.Table_9.9.length (Number of characters in string) : [example](02_Use_PostgreSQL/current/02_II/09/04/Table_9.9./01_length.md)  
║&ensp; &ensp; ║&ensp; &ensp;&nbsp;╠═9.4.Table_9.9.regexp_replace (Replace substring matching a POSIX regular expression) : [example](02_Use_PostgreSQL/current/02_II/09/04/Table_9.9./02_regexp_replace.md)  
║&ensp; &ensp; ║&ensp; &ensp;&nbsp;╚═9.4.Table_9.9.regexp_split_to_table (Split string using a POSIX regular expression as the delimiter) : [example](02_Use_PostgreSQL/current/02_II/09/04/Table_9.9./03_regexp_split_to_table.md)  
║&ensp; &ensp; ╠═9.7. [Pattern Matching](https://www.postgresql.org/docs/current/static/functions-matching.html)  
║&ensp; &ensp; ║&ensp;╚═9.7.3. [POSIX Regular Expressions](https://www.postgresql.org/docs/current/static/functions-matching.html#FUNCTIONS-POSIX-REGEXP)  
║&ensp; &ensp; ║&ensp; &ensp;&nbsp;╠═9.7.3.1 [Regular Expression Details](https://www.postgresql.org/docs/current/static/functions-matching.html#POSIX-SYNTAX-DETAILS)  
║&ensp; &ensp; ║&ensp; &ensp;&nbsp;║&ensp;╠═[Table 9.16. Regular Expression Quantifiers](https://www.postgresql.org/docs/current/functions-matching.html#POSIX-QUANTIFIERS-TABLE)  
║&ensp; &ensp; ║&ensp; &ensp;&nbsp;║&ensp;║&ensp; ╚═{m,n} : a sequence of m through n matches of the atom : [example](02_Use_PostgreSQL/current/02_II/09/07/3/1/01_matches_of_atom.md)  
║&ensp; &ensp; ║&ensp; &ensp;&nbsp;║&ensp;╚═[Table 9.17. Regular Expression Constraints](https://www.postgresql.org/docs/current/static/functions-matching.html#POSIX-CONSTRAINTS-TABLE)  
║&ensp; &ensp; ║&ensp; &ensp;&nbsp;║&ensp; &ensp; ╠═(?=re) : positive lookahead : [example](02_Use_PostgreSQL/current/02_II/09/07/3/1/02_positive_lookahead.md)  
║&ensp; &ensp; ║&ensp; &ensp;&nbsp;║&ensp; &ensp; ╚═(?!re) : negative lookahead : [example](02_Use_PostgreSQL/current/02_II/09/07/3/1/03_negative_lookahead.md)  
║&ensp; &ensp; ║&ensp; &ensp;&nbsp;╚═9.7.3.2 [Bracket Expressions](https://www.postgresql.org/docs/current/static/functions-matching.html#POSIX-BRACKET-EXPRESSIONS)  
║&ensp; &ensp; ║&ensp; &ensp;&ensp; &nbsp; ╚═9.7.3.2.1 [Bracket Expressions : examples](02_Use_PostgreSQL/current/02_II/09/07/3/2/01_Bracket_Expressions.md)  
║&ensp; &ensp; ╚═9.21. [Window Functions](https://www.postgresql.org/docs/current/static/functions-window.html)  
║&ensp; &ensp; &nbsp; &ensp;╚═9.21.1. [row_number() by column with partition](02_Use_PostgreSQL/current/02_II/09/21/06_row_number.md)  
╠═III. [Server Administration](https://www.postgresql.org/docs/current/static/admin.html)  
║&ensp;╚═19. [Server Configuration](https://www.postgresql.org/docs/current/static/runtime-config.html)  
║&ensp; &ensp; ╚═19.8. [Error Reporting and Logging](https://www.postgresql.org/docs/current/static/runtime-config-logging.html)  
║&ensp; &ensp; &ensp; &nbsp;╚═[example : configure postgresql.conf for query Logging](02_Use_PostgreSQL/current/03_III/19/08/01_configure_postgresql_conf_file.md)  
╠═VI. [Reference](https://www.postgresql.org/docs/current/static/reference.html)  
║&ensp;╠═I. [SQL Commands](https://www.postgresql.org/docs/current/static/sql-commands.html)  
║&ensp;║&ensp;╠═[GRANT](https://www.postgresql.org/docs/current/static/sql-createdatabase.html)  
║&ensp;║&ensp;║&ensp;╚═[example_GRANT_ALL_privileges](02_Use_PostgreSQL/current/06_VI/01_I/GRANT/01_GRANT_ALL_privileges.md)  
║&ensp;║&ensp;╠═[CREATE DATABASE](https://www.postgresql.org/docs/current/static/sql-createdatabase.html)  
║&ensp;║&ensp;║&ensp;╚═[example_CREATE_DATABASE](02_Use_PostgreSQL/current/06_VI/01_I/CREATE_DATABASE/01_CREATE_DATABASE.md)  
║&ensp;║&ensp;╠═[CREATE ROLE](https://www.postgresql.org/docs/current/static/sql-createrole.html)  
║&ensp;║&ensp;║&ensp;╚═[example_CREATE_ROlE](02_Use_PostgreSQL/current/06_VI/01_I/CREATE_ROLE/01_Create_Role.md)  
║&ensp;║&ensp;╠═[CREATE TABLE](https://www.postgresql.org/docs/current/static/sql-createtable.html)  
║&ensp;║&ensp;║&ensp;╚═[example_CREATE_TABLE](02_Use_PostgreSQL/current/06_VI/01_I/CREATE_TABLE/02_Create_Table.md)  
║&ensp;║&ensp;╠═[DELETE TABLE](https://www.postgresql.org/docs/current/static/sql-delete.html)  
║&ensp;║&ensp;║&ensp;╚═[example DELETE_duplicated_rows](02_Use_PostgreSQL/current/06_VI/01_I/DELETE/01_delete_duplicated_rows.md)   
║&ensp;║&ensp;╠═[INSERT INTO TABLE](https://www.postgresql.org/docs/current/static/sql-insert.html)  
║&ensp;║&ensp;║&ensp;╚═[example INSERT INTO TABLE with a row](02_Use_PostgreSQL/current/06_VI/01_I/INSERT/01_Insert_Into_Table.md)  
║&ensp;║&ensp;╚═[UPDATE](https://www.postgresql.org/docs/current/static/sql-update.html)  
║&ensp;║&ensp; &ensp; ╚═[example UPDATE_rows](02_Use_PostgreSQL/current/06_VI/01_I/UPDATE/01_update_table.md)  
║&ensp;╚═II.[PostgreSQL Client Applications](https://www.postgresql.org/docs/current/static/reference-client.html)  
║&ensp; &ensp; ╚═[pg_restore](https://www.postgresql.org/docs/current/static/app-pgrestore.html)  
║&ensp; &ensp; &ensp; &nbsp;╚═[Import_MySQL_sakila_sample_dataset_file_to_Postgresql_Database.sql](02_Use_PostgreSQL/current/06_VI/02_II/pg_restore/01_Import_MySQL_sakila_sample_dataset_to_PostgreSQL.md)  
╚═VIII. [Appendixes](https://www.postgresql.org/docs/current/static/appendixes.html)  
&ensp; &nbsp;╚═F. [Additional Supplied Modules](https://www.postgresql.org/docs/current/static/contrib.html)  
&ensp; &ensp; &nbsp; ╚═F.39 [tablefunc](https://www.postgresql.org/docs/current/static/tablefunc.html)  
&ensp; &ensp; &ensp; &nbsp; &nbsp;╚═F.39.1.4 [crosstab : Pivot_Table.sql](02_Use_PostgreSQL/current/08_VIII/F/39/01_Pivot_Table.md)  
( ║ ╠ ═ ╚ )  

# Not registed Use Case
[COPY table between file](02_Use_PostgreSQL/07_copy_table_and_file.md)  
[STRING AGG with ORDER BY](02_Use_PostgreSQL/08_STRING_AGG_ORDER_BY.md)  

# Use ToadPole
[Install and Use ToadPole for Postgresql](03_Use_Toad_Pole/01_use_toadpole.md)
