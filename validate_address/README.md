
# Address Validation (GAS)

## Overview
This script validates address data before it is processed in downstream operations.

The goal is not strict validation, but reducing errors while allowing acceptable variations.

---

## Problem
Address data often contained inconsistencies such as:
- format differences
- missing components
- non-standard inputs

Strict validation would reject valid cases, while no validation would increase downstream errors.

---

## Approach
- Implemented rule-based validation for common patterns
- Allowed flexible handling for acceptable variations
- Focused on reducing obvious errors without blocking valid inputs

---

## Design Decision
Instead of enforcing strict validation, I chose a balanced approach:
- prevent clear errors
- allow non-critical variations
- maintain operability

---

## Trade-off
- Some edge cases may still pass validation
- However, overall operational friction is significantly reduced

---

## Result
- Reduced manual correction workload
- Improved data consistency
- Stabilized downstream processes

---

## Positioning
This is an example of designing data validation under real operational constraints, where perfect data is not always achievable.
