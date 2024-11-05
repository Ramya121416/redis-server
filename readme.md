**build your own redis-server** 

Redis stores data in key-value pairs.
Support basic types like strings, lists, sets, hashes, and sorted sets.
Redis offers in-memory storage with options to persist data to disk.
Redis is single-threaded, handling one command at a time, but it’s highly optimized for fast performance.

when ever the web server  send any request to database then firstly it will check at redis cache 
        **if not found (cache missing) then it will check at database and stores in the redis and gives result back**
        **if found in redis(cache in), it will directly shows the result**
        

