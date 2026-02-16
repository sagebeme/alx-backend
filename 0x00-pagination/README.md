0x00. Pagination
================

This project practices **API pagination**: returning paginated results (page and page size) and optionally hypermedia links (next/prev page). Common in REST APIs to avoid returning huge lists.

Tasks
-----

### 0. Simple pagination helper

mandatory

Implement a simple pagination helper: given a dataset and request parameters `page` and `page_size`, return the correct slice of data and metadata (e.g. total pages, next/prev). The goal is to avoid loading entire collections in one response. Run: start the API (e.g. Flask) and request `GET /api/...?page=1&page_size=10`.

**Repo:**

-   GitHub repository: `alx-backend`
-   Directory: `0x00-pagination`
-   File: (main pagination module or view as per project)

---

**How to run / test**

1. Install dependencies (e.g. `pip install -r requirements.txt`).
2. Run the app and call the paginated endpoint with `page` and `page_size` query parameters.
3. Verify that only the requested slice is returned and that next/prev links work when required.
