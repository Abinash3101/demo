# Radme 2

Hello world again

## 2nd Title

learn git hub from zero to hero after adding worst branch

some text added yes yes yes

use mydb;

create table product(
id int PRIMARY KEY,
name varchar(20),
description varchar(100),
price decimal(8,3) 
);

select * from product;

user lacks privilege or object not found: PRODUCT / Error Code: -5501 / State: 42501

===============
Search search = new Search.Builder(filterQuery)
                .addIndex(indexAlias).addType(ELASTICSEARCH_INDEX_TYPE_PRODUCT).setParameter(PREFERENCE_PARAM, SHARD_PREFERENCE_PRIMARY_FIRST).build();
        ==============
		
        SearchRequest searchRequest = new SearchRequest(); 
        SearchSourceBuilder searchSourceBuilder = new SearchSourceBuilder(); 
        searchSourceBuilder.query(QueryBuilders.matchAllQuery()); 
        searchRequest.indices(indexAlias).searchType(ELASTICSEARCH_INDEX_TYPE_PRODUCT).source(searchSourceBuilder);