# Security policy

## Reporting

Do not open a public issue containing credentials, tokens, private endpoints, personal data, exploit details, or sensitive cloud identifiers. Contact the repository owner privately through an approved channel and rotate any exposed credential immediately.

## Repository hygiene

Before linking or promoting a repository in this catalog:

- scan Git history and the working tree for secrets
- remove kubeconfig files, Terraform state, `.env` files, private keys, and tokens
- use placeholders for account IDs, ARNs, endpoints, and resource IDs
- document IAM and public-network exposure
- identify resources that incur cost
- include cleanup instructions
- pin dependencies and container image versions appropriately
- enable GitHub secret scanning and dependency alerts where available

## Example safety

Examples are educational and must be reviewed for the target environment. Never treat workshop defaults such as unrestricted CIDRs, simple passwords, or administrator access as production recommendations.
