# saudi_geo_clickhouse

Saudi Arabia polygon data is uploaded in this repository, it has District and City Polygon as regions are easiy available online.

I have uploaded SQL statment sample to create a table on clikchouse with polygon values.

I believe it is hard to find the how to create table and insert query into CH expecially Polygon values, because i have found it difficult to find.

--Details on SQL statment
The poly column is loaded in order to execute pointInPolygon() CH function.

Data Loaded into this table is in format which is used for Apache superset deck.gl polygon, so feel free to change the format as required. 

Following link i refered 

https://pachicohub.com/posts/clickhouse-geo-search/
https://github.com/ClickHouse/ClickHouse/issues/9002
https://github.com/homaily/Saudi-Arabia-Regions-Cities-and-Districts

