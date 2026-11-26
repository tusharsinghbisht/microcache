# microcache

A small key-value store in Go, shipped as a single binary, with replication.

Work in progress. Nothing here is usable yet.

## Goals

- Single static binary, no external dependencies at runtime
- gRPC API for get, set, delete and TTLs
- Leader/follower replication
- Simple, readable code over feature count

## Planned

- [ ] In-memory store with sharded locking
- [ ] TTL expiry and eviction
- [ ] gRPC server and CLI
- [ ] Append-only log for persistence
- [ ] Replication
- [ ] Benchmarks

## License

MIT
