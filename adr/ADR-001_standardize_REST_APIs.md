# ADR-001: Standardize on REST APIs

**Status:** Accepted  
**Date:** 2023-08-15

## Context

As Atlas has grown, different teams have adopted different approaches for exposing application functionality. This has resulted in inconsistent API conventions, increased client complexity, and duplicated documentation.

## Decision

Northstar Engineering will standardize on REST-based APIs for all new services.

Existing services may continue using legacy interfaces until they are modified as part of normal development.

## Consequences

### Positive

- Consistent client development
- Simpler documentation
- Easier automated testing
- Reduced onboarding time for new engineers

### Negative

- Legacy interfaces will remain for some time.
- Multiple API styles will temporarily coexist during migration.

## Status

Implementation will occur incrementally as services are updated.
