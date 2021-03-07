# Migrate RDB to AOF

## Dump data to appendonly.aof

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
