# 2. Use ACM for All Certificates
Date: 2025-10-20

## Status

✅ Accepted

## Context

The MoJ currently uses Gandi Certificates for public certificates which require private keys. AWS Certificate Manager now supports exporting private keys for public certificates. By moving to ACM we reduce costs, manage certificates via code and can develop a visible documented process for easier renewals.

## Decision

- We will use ACM for Public Certificates which require private keys
- Certificates will be defined in code
- Certificates will be created in ACM in the user's account or the Modernisation Platform Network Services account


## Consequences

- New process needs to be documented
- Hosting Networking Group members need the knowledge and access to perform renewals or new requestes
- All new certificates will be issued via ACM.
