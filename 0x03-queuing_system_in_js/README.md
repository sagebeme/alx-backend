0x03. Queuing system in JS
==========================

This project builds a **job queuing system** in JavaScript using **Redis**: producers add jobs to a queue, workers process them (e.g. with Bull or Kue), and you practice async job handling and Redis data structures.

Tasks
-----

### 0. Queuing system (Redis + JS)

mandatory

Implement a queue: create a queue (e.g. with Bull), add jobs (with type and data), and run a worker that processes jobs (e.g. logs or performs a task). Redis is used as the backing store. Run: start Redis, run the worker, then add jobs (e.g. via a script or API) and watch the worker process them.

**Repo:**

-   GitHub repository: `alx-backend`
-   Directory: `0x03-queuing_system_in_js`
-   File: (queue module, worker, and job producer as per project)

---

**How to run / test**

1. Install Node deps and start Redis (`redis-server`).
2. Run the worker (e.g. `node worker.js`), then add jobs and confirm they are processed.
