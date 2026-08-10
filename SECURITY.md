# Security policy

Never commit tokens, keys, production credentials or user data, biometric
evidence, raw or unencrypted private media, private messages, recordings, or
unredacted message content. Reproduce security failures with synthetic
fixtures. Pull-request jobs must remain credential-free; private
cross-organization integration may use the organization-managed
`TEST_FLEET_READ_TOKEN` only in explicitly gated workflows. Report
vulnerabilities privately to the production owner.
