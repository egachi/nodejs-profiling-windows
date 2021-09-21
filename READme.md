## Profilers
---

### How to use this app
---

#### High CPU
- To simulate High CPU you can request the following route: **`/cpu/:id`**
- Example: `/cpu/45`

#### High Memory
- To consume memory you can request the following route: **`/memory`** , this endpoint will consume 200MB in each request.

#### Showing current memory and cpu time with NodeJS
- You can request **`/process`** and will see the memory allocation and cpu in microseconds.

#### Stop Profiler and get data
- You can request **`/end`** to exit node process and create the output either .cpuprofile or .heapprofile.

