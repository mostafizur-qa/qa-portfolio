# BUG-003 — Text encoding issue on payment page

**Severity:** Low  
**Priority:** P3  
**Environment:** Chrome (Desktop)

## Description
Special characters appear incorrectly (encoding artifact) on the payment instructions page.

## Steps to Reproduce
1. Open https://www.arngren.net/kjop.html
2. Review text content

## Expected Result
Characters display properly.

## Actual Result
Encoding artifacts observed (example: “12 Ã¥r”).

## Notes
Likely character encoding mismatch (UTF-8 vs other).
