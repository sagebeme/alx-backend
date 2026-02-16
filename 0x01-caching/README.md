0x01. Caching
=============

This project practices **caching** for backend APIs: storing responses or computed results (e.g. in Redis or in-memory) so repeated requests are faster and the origin is not overloaded.

Tasks
-----

### 0. Caching layer

mandatory

Implement a caching layer: when a request comes in, check if the result is already in the cache (e.g. by URL or key); if so return it, otherwise compute or fetch, store in cache with optional TTL, and return. You may use Redis or a simple in-memory store. Run: start the API and repeat the same request to see cache hits.

**Repo:**

-   GitHub repository: `alx-backend`
-   Directory: `0x01-caching`
-   File: (caching module or decorator as per project)

---

**How to run / test**

1. Install Redis if required and start the server.
2. Run the API and perform the same request twice; the second time should be served from cache when implemented.
