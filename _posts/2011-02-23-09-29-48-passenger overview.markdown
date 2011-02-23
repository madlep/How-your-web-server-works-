# Passenger #
- Loads Rails/app code once. Forks workers to save memory
- Apache still does heavy lifting, Passenger does rails
- Each Passenger worker process single threaded
- Makes app deployment easy, as all workers are managed by Apache
- Passenger has own worker/master pool. Not quite as battle hardened as Apache