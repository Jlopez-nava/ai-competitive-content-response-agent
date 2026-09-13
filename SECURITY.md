# Security Policy

## Public template scope

This repository contains a sanitized, disconnected Profound workflow template. It is intended to demonstrate the workflow architecture and provide a starting point for an authorized implementation.

The public files must not contain:

- API keys, tokens, passwords, credentials, cookies, or webhooks.
- Live Profound category, account, workspace, integration, or knowledge-base identifiers.
- Employer, client, customer, partner, or prospect information.
- Private competitor lists, positioning, audience definitions, or performance data.
- Generated articles, sales scripts, emails, citation results, or sentiment records from live runs.
- Local file paths or personal contact information.

All identifiers and organizations in the template are synthetic or generic. Reserved `.example` domains do not point to production services.

## Before using the workflow

1. Import the JSON only into a Profound workspace you are authorized to use.
2. Reconnect services through Profound's integration controls; do not paste secrets into prompts or committed JSON.
3. Keep live configuration and generated output in a private system with appropriate access controls.
4. Test with fictional or approved data before using real competitive intelligence.
5. Verify all generated sources, statistics, claims, and comparisons before publication or sales use.
6. Restrict control of the manual URL because it bypasses the workflow's thresholds.

## Reporting a problem

If you find sensitive information in this repository, do not open a public issue containing the information. Contact the repository owner privately and identify only the affected file and general issue type.
