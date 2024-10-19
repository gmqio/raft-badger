# Raft-badger is a full implementation [raft](github.com/hashicorp/raft) kv store based on [badger](https://github.com/dgraph-io/badger)

## Source code info

- log_store.go

```
raft log store based on badger
```

- stable_store.go

```
stable log store based on badger ( for config)
```

- fsm.go

```
fsm store based on badger ( for client)
```

## Quick start
[braftd](https://github.com/gmqio/braftd)