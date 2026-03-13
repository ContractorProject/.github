# ContractorProject

ContractorProject is a modular platform composed of a frontend SPA, a backend API, and local infrastructure tooling for fast onboarding.

## Repositories

| Repository | Purpose | Stack | Docs |
| --- | --- | --- | --- |
| [`contractor-fe`](https://github.com/ContractorProject/contractor-fe) | Frontend application for the platform | React Router SPA | [`README`](https://github.com/ContractorProject/contractor-fe#readme) |
| [`contractor-api`](https://github.com/ContractorProject/contractor-api) | Core API services | NestJS | [`README`](https://github.com/ContractorProject/contractor-api#readme) |
| [`proxy`](https://github.com/ContractorProject/proxy) | Docker-based local onboarding and infrastructure helpers | Docker | [`README`](https://github.com/ContractorProject/proxy#readme) |

## Documentation Conventions

To keep docs consistent across repositories:

- Put setup and development quickstart in each repo's root `README.md`.
- Add architecture notes under `docs/architecture/`.
- Add integration and runbook content under `docs/runbooks/`.
- Keep API endpoint or contract docs close to the service that owns them.

## Working Agreements

- Use pull requests for all changes to default branches.
- Prefer rebase merges to keep history linear.
- Keep `.env.example` up to date when configuration changes.

## Maintainers

For access, onboarding help, or incident escalation, contact the ContractorProject maintainers.