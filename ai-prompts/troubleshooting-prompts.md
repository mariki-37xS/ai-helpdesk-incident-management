# AI Troubleshooting Prompt Library

## Overview

This library demonstrates how artificial intelligence
can assist IT support analysts with incident management,
technical troubleshooting, and knowledge management.

AI recommendations must be reviewed and validated
by a human analyst before implementation.

## Prompt 001 - VPN Connection Failure

Act as an IT support analyst.

A remote employee cannot connect to the corporate VPN
despite having an active internet connection.

Provide:
- Possible causes.
- Step-by-step troubleshooting recommendations.
- Security considerations.
- Escalation criteria.
- Resolution verification steps.

Related incident: [INC001](../incidents/INC001.md)

## Prompt 002 - Employee Account Lockout

Act as an identity and access management support analyst.

An employee is locked out of their account following
multiple unsuccessful login attempts.

Provide:
- Possible causes of the account lockout.
- Secure identity verification procedures.
- Authorized account recovery recommendations.
- Security risks and escalation criteria.
- Steps to verify successful account recovery.

Related incident: [INC002](../incidents/INC002.md)

## Prompt 003 - Incident Classification

Act as an IT service desk analyst.

Review a simulated incident description and recommend:
- Incident category and subcategory.
- Business impact.
- Urgency.
- Priority based on the approved priority matrix.
- Appropriate assignment group.
- Recommended next actions.

Explain the reasoning behind each recommendation.

## Prompt 004 - Knowledge Base Generation

Act as an IT knowledge management specialist.

Using verified incident resolution notes, generate
a knowledge base article containing:

- Problem description.
- Common symptoms.
- Possible causes.
- Troubleshooting procedures.
- Security considerations.
- Expected results.
- Escalation procedures.

## Responsible AI Usage

- Never share passwords or confidential information.
- Never share MFA verification codes.
- Use only authorized and sanitized incident data.
- Validate AI-generated recommendations.
- Follow organizational security policies.
- Escalate suspicious activity.
- Maintain human oversight and accountability.
- Never invent investigation findings.

## Human Validation Checklist

- [ ] Review AI recommendations for accuracy.
- [ ] Verify findings against available evidence.
- [ ] Confirm compliance with security policies.
- [ ] Obtain required authorization.
- [ ] Verify the resolution.
- [ ] Document the final outcome.

## Project Note

These prompts are designed for simulated IT support
scenarios and professional portfolio development.
They do not represent a live AI integration.
