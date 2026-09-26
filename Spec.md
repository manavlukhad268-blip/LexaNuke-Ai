# Technical Specification: LexNuke AI

## System Architecture

- **Frontend Framework:** Next.js / React (Tailwind CSS for responsive styling).
- **Deployment Platform:** Bolt.new / Web Container platform.
- **Cryptographic Hashing:** Client-side / Server-side SHA-256 evidence hashing for cryptographic proof.

## Data Flow & Processing Pipeline

1. **Ingress Stage:** User inputs `URL` or `File Buffer`.
2. **Analysis Stage:** Payload triggers mock audit engine, outputting breach confidence (`0-100%`) and forensic metadata.
3. **Hashing Stage:** Payload content & timestamp compiled into a SHA-256 digest string (`e.g., c20bc60046dac...`).
4. **Notice Drafting:** Inject metadata into predefined legal cease-and-desist templates.
5. **Dispatch Stage:** Mock API trigger dispatches payload to hosting provider abuse emails (`abuse@hosting-provider.net`).
