# Security Policy

This repository is a public learning and portfolio repository.

## Never commit

- Passwords or API keys
- Cloud access keys or service-account credentials
- Private keys or certificates
- Production IP addresses or internal hostnames
- Customer or employee data
- Employer or client documents
- Internal architecture diagrams
- Screenshots containing confidential information
- Secrets from lab or production environments

## Portfolio rule

Use sanitized examples, synthetic data and lab-only infrastructure.

If an exercise comes from real work experience, document the general engineering lesson without exposing confidential implementation details, customer information, credentials, internal systems or proprietary material.

## Before every commit

Ask:

1. Does this reveal a secret or credential?
2. Does this expose an employer or client environment?
3. Could this information help someone target a real system?
4. Can I recreate the same lesson safely in a lab instead?

If the answer to any of the first three questions is yes, do not publish it.
