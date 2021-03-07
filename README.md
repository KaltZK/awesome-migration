
# Redis

## RDB to AOF

In redis-cli
```
save
CONFIG SET appendonly yes
save
shutdown save
```
