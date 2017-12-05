# wblotevogel.redis
ansible role for installation of Redis

simple installation which bind with the standard host IP an set up a couple memory variables. read the redis.conf.j2 (or /etc/redis/redis.conf once installed) if you to change them or add more.

# variables
redis_maxmemory: "maxmemory 500mb"
redis_maxmemory_policy: "maxmemory-policy allkeys-lru"
