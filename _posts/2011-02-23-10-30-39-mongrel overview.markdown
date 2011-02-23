# Mongrel /Rails #
- Start up multiple mongrel processes manually (supermarket checkouts)
- Best practice for Rails apps for a while, but Passenger more used now
- Each has full Rails stack loaded (more memory usage)
- Each single threaded with own queue
- Needs front end round robining requests to mongrels
- Long running requests mean wait for all queued on that mongrel
