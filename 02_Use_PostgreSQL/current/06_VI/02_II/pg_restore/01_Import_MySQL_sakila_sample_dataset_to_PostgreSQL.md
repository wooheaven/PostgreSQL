# Import [ MySQL sakila sample dataset ] to PostgreSQL
Reference  
&emsp;http://www.postgresqltutorial.com/postgresql-sample-database/  
PostgreSQL Current Document  
&emsp;https://www.postgresql.org/docs/current/static/app-pgrestore.html

```{bash}
$ wget http://www.postgresqltutorial.com/wp-content/uploads/2017/10/dvdrental.zip
$ unzip dvdrental.zip
Archive:  dvdrental.zip
  inflating: dvdrental.tar
$ pg_restore -U postgres -d postgres dvdrental.tar
$ psql -U postgres -d postgres
```
```{sql}
postgres=# \d
                      List of relations
 Schema |             Name              |   Type   |  Owner
--------+-------------------------------+----------+----------
 public | actor                         | table    | postgres
 public | actor_actor_id_seq            | sequence | postgres
 public | actor_info                    | view     | postgres
 public | address                       | table    | postgres
 public | address_address_id_seq        | sequence | postgres
 public | category                      | table    | postgres
 public | category_category_id_seq      | sequence | postgres
 public | city                          | table    | postgres
 public | city_city_id_seq              | sequence | postgres
 public | country                       | table    | postgres
 public | country_country_id_seq        | sequence | postgres
 public | customer                      | table    | postgres
 public | customer_customer_id_seq      | sequence | postgres
 public | customer_list                 | view     | postgres
 public | departments                   | table    | postgres
 public | departments_department_id_seq | sequence | postgres
 public | employees                     | table    | postgres
 public | employees_employee_id_seq     | sequence | postgres
 public | film                          | table    | postgres
 public | film_actor                    | table    | postgres
 public | film_category                 | table    | postgres
 public | film_film_id_seq              | sequence | postgres
 public | film_list                     | view     | postgres
 public | inventory                     | table    | postgres
 public | inventory_inventory_id_seq    | sequence | postgres
 public | language                      | table    | postgres
 public | language_language_id_seq      | sequence | postgres
 public | nicer_but_slower_film_list    | view     | postgres
 public | payment                       | table    | postgres
 public | payment_payment_id_seq        | sequence | postgres
 public | rental                        | table    | postgres
 public | rental_rental_id_seq          | sequence | postgres
 public | sales_by_film_category        | view     | postgres
 public | sales_by_store                | view     | postgres
 public | staff                         | table    | postgres
 public | staff_list                    | view     | postgres
 public | staff_staff_id_seq            | sequence | postgres
 public | store                         | table    | postgres
 public | store_store_id_seq            | sequence | postgres
(39 rows)
```
