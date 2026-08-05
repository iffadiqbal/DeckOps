# DeckOps
The future of all CRMS, ERMS, and ticketing systems. Made for small business', this will be a all-in-one place tool to server your backend needs as you move through your business. 

The Deck is an enterprise-grade, offline-first field service operating system purpose-built for independent technical contractors. Bypassing the bloated, expensive features of traditional fleet-focused CRMs, it delivers a lean, high-performance dispatch, estimating, and billing engine. Architected on a decoupled stack using Netlify and Supabase, it provides a zero-latency experience for technicians in the field while maintaining strict, database-level security and seamless client-facing interactions.

Here are the core technical and sales features that define the platform:

Offline-First Resilience: Engineered with optimistic UI updates and a local outbox queue, ensuring zero data loss and instant interaction even in dead zones (like concrete basements or high-rises), syncing silently via Supabase Realtime when the connection is restored.

Enterprise-Grade Security: Utilizes PBKDF2 hashing and Row Level Security (RLS) to enforce strict, database-level role-gating—such as completely hiding financial margins and pricing from standard staff while protecting data integrity.

Client-Facing Quote Portal: A dedicated, secure public view accessed via 122-bit cryptographic tokens allows clients to review line-item breakdowns, taxes, and discounts, and legally accept quotes with a digital signature without ever needing a login.

Dynamic Estimator & Automated Procurement: Quotes are built dynamically from a managed price book; any required SKUs automatically populate a "To Order" ledger the moment a job is scheduled, complete with automatic supplier detection.

Optimized Media Storage: Integrates Supabase Storage with on-device, client-side HTML5 canvas compression, shrinking heavy high-res before-and-after site photos to a fraction of their size before hitting the network to preserve bandwidth and storage quotas.

Built-In Growth Engine: Features a native referral ledger that tracks and rewards client referrals automatically, applying margin-protected discounts and turning an existing customer base into a trackable sales team.
