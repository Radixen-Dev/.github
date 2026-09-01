# Contributing

Radixen repositories use pull requests for authored changes to protected integration branches.

## Workflow

1. Create a short-lived branch from the current integration branch.
2. Make the smallest coherent change that satisfies the issue/goal.
3. Update affected tests, contracts, documentation, security/privacy inventories, or runbooks in the same change when applicable.
4. Open a pull request using the organization template.
5. Resolve required checks and review conversations before merge.

Direct pushes and force pushes to protected branches are not part of the normal workflow.

## Branch names

Use a short category and purpose, for example:

- `feat/...`
- `fix/...`
- `docs/...`
- `infra/...`
- `security/...`
- `refactor/...`
- `chore/...`
- `spike/...`

## Pull requests

Do not leave applicable risk categories unconsidered. `N/A` is valid when a section genuinely does not apply.

A change that makes authoritative documentation false should update that documentation as part of the same work whenever practical.

## Security and sensitive data

Never commit production credentials, secrets, private authentication material, or copied production personal data. Use synthetic examples and the repository's approved secret-management mechanism.

Security-sensitive implementation details should remain in private project repositories when public disclosure is not appropriate.

## Repository-specific rules

Repository-local contribution and governance documentation may add stricter requirements. Where they conflict with this organization default, the stricter applicable project rule takes precedence unless an accepted project decision says otherwise.
