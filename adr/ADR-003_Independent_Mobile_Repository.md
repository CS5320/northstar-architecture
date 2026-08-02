# ADR-003: Independent Mobile Repository

**Status:** Accepted  
**Date:** 2024-01-18

## Context

The mobile application follows a different release cadence than the platform services and often requires independent testing and deployment.

Maintaining all components within a single repository has slowed development and complicated release management.

## Decision

The mobile application will be maintained in its own repository while continuing to consume shared platform APIs.

## Consequences

### Positive

- Independent release schedule
- Smaller codebase for mobile developers
- Clearer ownership boundaries

### Negative

- Shared models require additional coordination.
- API compatibility must be maintained across repositories.

## Notes

Platform APIs should remain backward compatible whenever practical.
