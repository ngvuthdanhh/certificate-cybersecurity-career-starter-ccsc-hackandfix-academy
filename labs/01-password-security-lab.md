# Lab 01 — Password Security Validation

## Objective
Learn how weak password policies expose systems to brute force, dictionary attacks, and credential stuffing, and document secure alternatives.

## Tasks
1. Create a sample password complexity rule.
2. Test common weak password patterns.
3. Build a blacklist of predictable passwords.
4. Evaluate length vs complexity trade-offs.

## Validation Criteria
- Minimum length: 12–16 characters
- No personal identifiers
- No sequential or repetitive characters
- Must not match common breach-leaked passwords
- Prefer randomly generated phrases or strings

## Expected Output
A short report documenting:
- Weak patterns identified
- Policy improvement suggestions
- Secure password examples

## Safe Example Passwords
- correct-horse-battery-staple-2025
- P@55w0rd!123 → (flagged: predictable pattern)
- 4&9$kLq!mZ*2#8 → (strong: random, long, non-patterned)
