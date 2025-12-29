# Product Problem Landscape — React / Next.js

This document summarizes key developer experience problems identified through analysis of GitHub issues, discussions, RFC feedback, and community questions in the React / Next.js ecosystem.

## Key Problem Areas

### 1. App Router Onboarding
- New developers struggle to understand the server-first architecture
- Documentation explains features but not decision-making

### 2. Server vs Client Components
- Confusion about when a component should be client-side
- Overuse of the `use client` directive

### 3. Migration from Pages Router
- Lack of a clear, step-by-step migration mental model
- Fear of breaking existing applications

### 4. Data Fetching Responsibilities
- Unclear boundaries between server and client data fetching
- Misalignment with prior React mental models

## Observation
Most issues stem from **mental model gaps**, not missing APIs or features.
