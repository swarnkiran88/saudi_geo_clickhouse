# saudi_geo_clickhouse

Saudi Arabia polygon data is uploaded in this repository, it has District and City Polygon as regions are easiy available online.

I have uploaded the sample how to create a table to geospatial data into clikchouse
I believe it is hard to find the how to create table and insert query for CH, because i have found it difficult.

The poly column is loaded so that it can be used in execution of  pointInPolygon() CH function.

Data Loaded into this table is in format to represent the data in Apache superset deck.gl polygon, so feel free to change the gjson format as required. 

Following link i refered 

https://pachicohub.com/posts/clickhouse-geo-search/
https://github.com/ClickHouse/ClickHouse/issues/9002

