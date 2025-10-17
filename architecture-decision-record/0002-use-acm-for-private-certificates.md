# 2. Use ACM for Private Certificates
Date: 2025-10-17

## Status

✅ Accepted

## Context

The MoJ currently uses Gandi Certificates for private certificates. AWS Certificate Manager now supports exporting private certificates. By moving private certificates to ACM we reduce costs, manage certificates via code and can develop a visible documented process for easier renewals.

## Decision

- We will use ACM for Private Certificate management
- Certificates will be defined in code
- Certificates will be created in the ACM in the Modernisation Platform Shared Services account

## Consequences

- New process needs to be documented
- Hosting Networking Group members need the knowledge and access to perform renewals or new requestes
- All new certificates will be issued via ACM.
