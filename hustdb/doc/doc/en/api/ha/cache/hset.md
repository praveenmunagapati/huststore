## hset ##

**Interface:** `/cache/hset`

**Method:** `GET | PUT | POST`

**Parameter:** 

*  **tb** (Required)  
*  **key** (Required)  
*  **val** (Required)  

This interface is a proxy interface for `/hustcache/hset`. See more details in [here](../../hustdb/hustcache/hset.md).  

**Sample:**

    curl -i -X GET "http://localhost:8082/cache/hset?tb=test_table&key=test_key&val=test_val"

[Previous](../cache.md)

[Home](../../../index.md)