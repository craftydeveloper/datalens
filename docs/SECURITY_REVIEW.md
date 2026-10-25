# Security review

## Product risks

Metrics without units, dates, and source context can mislead. Record transformation assumptions.

## Baseline

Treat imported text as untrusted, bound input sizes, avoid unsafe HTML insertion, keep credentials out of client code, and verify external links. This checklist is not a security certification.