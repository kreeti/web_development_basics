## REDIS Exercises

1. After executing following three commands in REDIS what’ll be the o/p of last command? Describe all of the commands.
    * zadd zset-1 1 a 2 b 3 c
    * zadd zset-2 4 b 1 c 0 d
    * zinterstore zset-i 2 zset-1 zset-2
    * zrange zset-i 0 -1 withscores

2. After executing following three commands in REDIS what’ll be the o/p of last command? Describe all of the commands.
    * RPUSH mylist "Hello"
    * RPUSH mylist "World"
    * LINSERT mylist BEFORE "World" "There"
    * LRANGE mylist 0 -1

3. After executing following two commands in REDIS what’ll be the o/p of last command? Describe all of the commands.
    * HSET myhash field1 "foo"
    * HDEL myhash field1
    * HDEL myhash field2

4. Explain with scenario where Set is most appropriate than List in Redis.

5. Explain with scenario where Hash is most appropriate than List.
