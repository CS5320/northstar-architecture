# ADR-002: Separate Authentication Service

**Status:** Accepted  
**Date:** 2023-10-02

## Context

Authentication logic was previously embedded throughout multiple services, resulting in duplicated authorization checks and inconsistent security behavior.

## Decision

Authentication and authorization responsibilities will be centralized within a dedicated Authentication Service.

Application services should delegate identity verification and authorization decisions whenever practical.

## Consequences

### Positive

- Consistent security model
- Reduced duplicated logic
- Easier compliance reviews
- Simplified future authentication enhancements

### Negative

- Increased dependency on the Authentication Service
- Temporary compatibility layer required for legacy applications

## Notes

Some legacy endpoints continue to use older authentication workflows and will be migrated over time.
