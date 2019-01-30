## MySQL Indexes

Get unused index on a MySQL Database

~~~~sql
select * from performance_schema.table_io_waits_summary_by_index_usage where object_schema = 'schema_name' and count_star = 0;
~~~~
