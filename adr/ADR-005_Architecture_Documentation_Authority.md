# ADR-005: Architecture Documentation Authority

**Status:** Accepted  
**Date:** 2024-08-27

## Context

Architecture documentation has gradually become inconsistent as the system has evolved.

Engineers have occasionally received conflicting guidance from diagrams, onboarding documentation, and implementation notes.

## Decision

Architecture Decision Records (ADRs) are considered the authoritative record of architectural decisions.

Supporting documentation should reference ADRs whenever possible and be updated as systems evolve.

## Consequences

### Positive

- Clear source of architectural truth
- Better historical record of engineering decisions
- Reduced ambiguity during future design discussions

### Negative

- ADRs require ongoing maintenance.
- Existing documentation may reference outdated architectural assumptions.

## Notes

When conflicts exist between documentation and ADRs, the ADR should be considered authoritative until updated by the Architecture Review Board.
