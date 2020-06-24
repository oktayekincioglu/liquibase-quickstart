mvn liquibase:update

# Liquibase 3.6.x data types mapping table

|Liquibase data type|SQL Server data type|Oracle data type|MySQL|PostgreSQL|
|--- |--- |--- |--- |--- |
|bigint|bigint|number(38,0)|bigint|bigint/bigserial|
|blob|varbinary(max)|blob|blob|oid|
|boolean|bit|number(1)|bit|bit|
|char|char|char|char|character|
|clob|nvarchar(max)|clob|longtext|text|
|currency|money|number(15,2)|decimal|decimal|
|datetime|datetime|timestamp|timestamp|timestamp|
|date|date|date|date|date|
|decimal|decimal|decimal|decimal|decimal|
|double|float|float(24)|double|double precision|
|float|float|float|float|float|
|int|int|integer|int|integer/serial|
|mediumint|int|mediumint|mediumint|mediumint|
|nchar|nchar|nchar|nchar|nchar|
|nvarchar|nvarchar|nvarchar2|nvarchar|varchar|
|number|numeric|number|numeric|numeric|
|smallint|smallint|number(5)|smallint|smallint/smallserial|
|time|time|date|time|time|
|timestamp|datetime|timestamp|timestamp|timestamp|
|tinyint|tinyint|number(3)|tinyint|smallint|
|uuid|uniqueidentifier|raw(16)|char(36)|uuid|
|varchar|varchar|varchar2|varchar|varchar/character (varying)|
