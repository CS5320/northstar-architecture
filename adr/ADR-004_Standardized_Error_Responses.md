# ADR-004: Standardize Error Responses

**Status:** Accepted  
**Date:** 2024-05-06

## Context

Application services currently return inconsistent error formats, making client development and troubleshooting more difficult.

Engineering teams have requested a common error structure.

## Decision

All newly developed APIs will return standardized error responses following the Northstar API Guidelines.

Legacy endpoints may continue using existing formats until modified.

## Consequences

### Positive

- Consistent client behavior
- Simpler API documentation
- Improved logging and monitoring
- Easier automated testing

### Negative

- Existing clients may require updates during migration.
- Legacy services will temporarily remain inconsistent.

## Notes

Migration should occur gradually during routine maintenance rather than through a dedicated project.
