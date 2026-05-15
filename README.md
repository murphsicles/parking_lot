# @sync/parking_lot — Fast Synchronization Primitives for Zeta

Auto-converted from [parking_lot](https://crates.io/crates/parking_lot) v0.12.5 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Types
- `Mutex<T>` — fast mutex (no poisoning)
- `RwLock<T>` — read-write lock
- `Once` — one-time initialization
- `Condvar` — condition variable
- `FairMutex<T>` — fair queuing mutex
- `ReentrantMutex<T>` — reentrant mutex
- `OnceCell<T>` — lazy one-value cell
- Guard types: MutexGuard, RwLockReadGuard, RwLockWriteGuard, etc.

## Stats
- 13 source files, ~2,157 lines
- 0 unsupported items
- All guard types preserved with lifetime parameters
