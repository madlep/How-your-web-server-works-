# Apache #
- Workers isolated, config can resource throttle if desired
- More secure. Workers not started as privileged user. No shared memory
- Workers can crash without affecting other requests
- OS level processes heavy on CPU/memory
- Finite workers. **FAIL** if all are blocking on resource that won't timeout
