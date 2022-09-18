# Week 51

## Geospatial  

GEOADD KEY long lat MEMBER
GEODIST key member1 member2 [unit] (return distance)

GEORADIUS key long lat (distance 4KM) [WITHDIST. WITHCOORDS, ...] (return points)
GEORADIUSBYMEMBER key member  distance

stored a GEOHASH number score
= Sorted set

GEOHASH key member
GEOPOS key member  (return X,Y points)

## Lua in Redis

"kind" of procedures

EVAL script numkeys keys [key ...] arg [arg ...]

redis.call
redis.pcall

SCRIPT LOAD script

EVALSHA sha1 numkeys key
SCRIPT EXISTS sha
SCRIPT FLUSH
SCRIPT KILL
