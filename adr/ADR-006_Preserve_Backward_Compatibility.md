# ADR-006: Preserve Backward Compatibility

**Status:** Accepted  
**Date:** 2025-02-11

## Context

Atlas supports several long-term enterprise customers who integrate directly with Northstar APIs. Breaking API changes have historically resulted in costly customer migrations.

## Decision

Backward compatibility should be preserved whenever practical. When incompatible changes are necessary, deprecation notices and migration guidance should be provided before removing existing functionality.

## Consequences

### Positive

- Reduced customer disruption
- Increased confidence in platform stability
- Easier long-term adoption

### Negative

- Legacy code may remain longer than desired.
- Technical debt may accumulate while supporting older interfaces.

## Notes

The Architecture Review Board may approve exceptions when the long-term benefits outweigh the migration costs.
