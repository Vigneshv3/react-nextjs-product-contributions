# Case Study: Improving Next.js App Router Onboarding

## Problem
New developers adopting the Next.js App Router struggle to understand the server-first architecture, leading to incorrect component usage, performance issues, and slower onboarding.

## Users
- New Next.js developers
- React developers migrating from the Pages Router

## Evidence
- Repeated GitHub issues and discussions asking similar questions
- Frequent misuse of the `use client` directive
- Confusion around data fetching responsibilities

## User Pain Points
- Lack of a clear mental model for server vs client rendering
- Documentation explains features but not decision-making
- Migration guides assume prior architectural knowledge

## Constraints
- Must preserve backward compatibility
- Cannot oversimplify core framework concepts
- Performance implications of incorrect patterns

## Proposed Solutions
1. Decision-based documentation explaining when to use Server vs Client Components
2. A dedicated App Router onboarding guide with progressive complexity
3. A “Common Mistakes” section addressing frequent misconceptions

## Success Metrics
- Reduction in repeated onboarding-related issues
- Faster time-to-first-correct-implementation
- Improved developer confidence

## Key Learning
Developer experience improves when documentation focuses on **how to decide**, not just **what to use**.
