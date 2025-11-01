# Database Learning - MySQL
> This is my note in learning MySQL 

### File Creation & Management 
- `create` `database`
- `drop` `database`
- `use` `database`
- `alter` `database`

### Table
- Creation
``` 
create table table_name(
    item1 int,
    item2 varchar(123),
    item3 decimal(123,123),
    item4 date
) 
```
- Insertion
    - single row
    ```
    insert into table_name (item1, item2, item3, item4)
    values (1, "Str Item", 123.123, 2025-11-01);
    select * from employees;
    ```
    - multi rows
    ```
    insert into table_name (item1, item2, item3, item4)
    values (1, "Str Item", 123.123, 2025-11-01)
    values (2, "Str Item", 123.123, 2025-11-01)
    values (3, "Str Item", 123.123, 2025-11-01)
    select * from employees;
    ```