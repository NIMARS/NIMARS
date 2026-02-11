# Roman — Backend Developer (Node.js / TypeScript)

Backend engineer focused on reliable HTTP APIs, data consistency and predictable behaviour.

---

## What to demo

**notes-api — indexing & pagination**  
Open `/docs` → GET `/notes?limit=20`  
Shows: cursor pagination + jsonb GIN filtering  
https://github.com/NIMARS/notes-api

**booking-api-demo — concurrency correctness**  
Send 2 parallel booking requests → one returns 409  
Shows: race condition handling & idempotency  
https://github.com/NIMARS/booking-api-demo

**all-about-pet — full auth lifecycle in real app**  
Login → refresh → protected route  
Shows: access/refresh rotation, RBAC, ownership checks, uploads  
https://github.com/NIMARS/all-about-pet

---

## What this proves  
- design APIs without duplicate/invalid states
- handle concurrent writes safely
- implement real authentication lifecycle
- ship reproducible services (tests + docker + docs)

---

## Links
Portfolio: https://nimars.github.io  
LinkedIn: https://www.linkedin.com/in/nimars
