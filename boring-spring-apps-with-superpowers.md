Boring Spring Apps with Superpowers
Active/Active with Spring and Redis

Abstract
Is your app alone and trembling in a dark, single region with failures, latency, and retry storms closing in on every side? What do you do when your mild-mannered application is in trouble and needs rescuing? In this session, we’ll show you how to turn that mild-mannered application into one with superpowers.

How do you ensure your application still functions if one data-center/region/cloud goes down? In this session, we will describe and demonstrate an active/active application (meaning read and write traffic is routed to two or more real-time, geo-distributed, multi-cloud locations). Using Spring and Redis, these applications turn out to be quite boring and super powerful.


Notes
Single region isn’t enough
how do you do with without wasting idle resources
For the whole of 8 years on spring cloud, folks while talking about distributed systems, rarely talk about the data layer. Netflix: cassandra and other replicated data (s3, redis/memcache/…)
I’ll never let my kids deploy active/passive
Ultimate demo: chaos monkey (instances), chaos gorilla (availability zone), chaos kong (region)
https://netflixtechblog.com/chaos-engineering-upgraded-878d341f15fa
Spring Tech
Highlight microservices (ie more than one app backed by redis)
spring data
spring cloud?
Redis Tech
Highlight redis features
milliseconds matter
data types (which are good for active/active)
streaming
search (reindexing at speed_
write through cache
Buffered Cache – Our RDBMS can’t write fast enough….
https://github.com/redis/redis-om-spring
Demo app theme (inspiration from redis bank)
stocks
