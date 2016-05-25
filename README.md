#  docker-redis

Redis - Social Tables Style

## Why

We like our Redis databases to:

- match the customized parameter group we apply to our Redis databases on AWS ElastiCache

Currently, this means that [keyspace event notifications](http://redis.io/topics/notifications)
are enabled for all events.

## Usage

```sh
docker-compose up -d
```
