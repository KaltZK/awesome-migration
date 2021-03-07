
# Redis

## RDB to AOF

In redis-cli

Bakcup data.
```
save
```

Enable appendonly mode.
```
CONFIG SET appendonly yes
```

Dump data into AOF file
```
save
```

Safely shutdown
```
shutdown save
```
