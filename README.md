# Install and Run PostgreSQL
&emsp;[Install PostgreSQL9.3.6 : on docker](01_Install_and_Run_PostgreSQL/01_Install_PostgreSQL9.3.6_on_docker.md)  
&emsp;[Run PostgreSQL9.3.6 : on docker](01_Install_and_Run_PostgreSQL/02_Run_PostgreSQL9.3.6_on_docker.md)

# Use PostgreSQL
| Document           | Part                      | Chapter                        | Head1                               | Head2                                         | Link of Details                                                                            |
|--------------------|---------------------------|--------------------------------|-------------------------------------|-----------------------------------------------|--------------------------------------------------------------------------------------------|
| PostgreSQL current | II. The SQL Language      | 9. Functions and Operators     | 9.4. String Functions and Operators | Table 9-8. SQL String Functions and Operators | [Concatenate Columns](02_Use_PostgreSQL/09_Concatenate_Columns.md)                         |
|                    |                           |                                | 9.21. Window Functions              | Table 9.57 General-Purpose Window Functions   | [row_number() : add row_number by partition and order](02_Use_PostgreSQL/06_row_number.md) |
|                    | VI. Reference             | I. SQL Commands                | CREATE TABLE                        | Example                                       | [CREATE TABLE](02_Use_PostgreSQL/02_Create_Table.md)                                       |
|                    |                           |                                | DELETE TABLE                        | Example                                       | [DELETE TABLE : delete rows which is duplicated](02_Use_PostgreSQL/12_delete_table.md)     |
|                    |                           |                                | UPDATE                              | Example                                       | [UPDATE rows](02_Use_PostgreSQL/11_update_table.md)                                        |
|                    | VIII. Appendixes          | F. Additional Supplied Modules | F.38. tablefunc                     | F.38.1.4. crosstab(text, text)                | [Pivot Table](02_Use_PostgreSQL/10_Pivot_Table.md)                                         |

# Use Case of PostgreSQL
| Use Case                                             | Reference          | Link                                                                                                              |
|------------------------------------------------------|--------------------|-------------------------------------------------------------------------------------------------------------------|
| Add column as SERIAL in order to prevent Duplication | 8.1.4 Serial Types | [SERIAL Types Use-Case-01](02_Use_PostgreSQL/current/2/08/01/4/01_add_column_as_serial_to_prevent_duplication.md) |

# Documents
[PostgreSQL current Documentation](https://www.postgresql.org/docs/current/static/index.html)  
&emsp;Table of Contents  
&emsp;&emsp;II. [The SQL Language](https://www.postgresql.org/docs/current/static/sql.html)  
&emsp;&emsp;&emsp;8. [Data Types](https://www.postgresql.org/docs/current/static/datatype.html)  
&emsp;&emsp;&emsp;&emsp;8.1. [Numeric Types](https://www.postgresql.org/docs/current/static/datatype-numeric.html)  
&emsp;&emsp;&emsp;&emsp;&emsp;8.1.4. [Serial Types](https://www.postgresql.org/docs/current/static/datatype-numeric.html#DATATYPE-SERIAL)  

# Not registed Use Case
[Configure Role, Database, Previlege](02_Use_PostgreSQL/01_Configure_Role_Database_Preivilege.md)

[Insert Into Table](02_Use_PostgreSQL/03_Insert_Into_Table.md)

[regexp_split_to_table](02_Use_PostgreSQL/04_regexp_split_to_table.md)

[regexp_matches](02_Use_PostgreSQL/05_regexp_matches.md)

[COPY table between file](02_Use_PostgreSQL/07_copy_table_and_file.md)

[STRING AGG with ORDER BY](02_Use_PostgreSQL/08_STRING_AGG_ORDER_BY.md)

# Use ToadPole

[Install and Use ToadPole for Postgresql](03_Use_Toad_Pole/01_use_toadpole.md)
