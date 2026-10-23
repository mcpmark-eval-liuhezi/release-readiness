# Go-Live Checklist

Use this checklist to confirm the product is ready to ship v1.

## Release Engineering

- [ ] Cut the v1 release branch
- [ ] Tag the release candidate (e.g. `v1.0.0-rc1`)
- [ ] Verify build artifacts are published and downloadable

## Quality Assurance

- [ ] Write the QA smoke test plan
- [ ] Run the full smoke-check suite (`.github/workflows/smoke-checks.yml`)
- [ ] Confirm zero open P0/P1 defects

## Documentation

- [ ] Update the customer-facing changelog
- [ ] Publish release notes to the docs site

## Operations

- [ ] Draft the rollback runbook
- [ ] Confirm on-call coverage for launch week

## Security

- [ ] Confirm security review sign-off
