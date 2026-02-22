# BUG-001 — Link opens 403 Forbidden

**Severity:** Medium  
**Priority:** P2  
**Environment:** Chrome (Desktop)

## Description
Clicking certain product/category links results in a 403 Forbidden response.

## Steps to Reproduce
1. Go to https://arngren.net/
2. Click a product/category link (example: “Alkotester”)

## Expected Result
Selected page loads successfully.

## Actual Result
Page fails to load and returns 403 Forbidden.

## Notes
Issue may be server-side access control or link routing.
