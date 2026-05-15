# @sync/parking_lot — Fast Synchronization Primitives for Zeta

Auto-converted from [parking_lot](https://crates.io/crates/parking_lot) v0.12.5 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features

| Type | Description |
|------|-------------|
| `Mutex<T>` | Fast mutex — no poisoning, const constructor, ~2x faster than std |
| `RwLock<T>` | Read-write lock — upgradable reads, fair/unfair policies |
| `Once` | One-time initialization — call_once, call_once_force |
| `Condvar` | Condition variable — wait, notify_one, notify_all, timed wait |
| `FairMutex<T>` | Fair queuing mutex — FIFO ordering guarantee |
| `ReentrantMutex<T>` | Reentrant mutex — same-thread recursive locking |

All types include full guard wrappers: MutexGuard, RwLockReadGuard, RwLockWriteGuard, MappedMutexGuard, MappedRwLockGuard, and their owned variants.

## Stats: 13 source files, ~2,157 lines, 0 unsupported items

## License
MIT