# AGENTS.md — Axodus organization profile

## Purpose

This repository is the versioned institutional representation of the local
Axodus workspace on GitHub. It owns organization-level presentation,
repository discovery, community files, and organization-specific automation.
It does not own product implementation or act as a monorepo for Axodus nuclei.

## Sources

- Use `../Documentation/docs/overview/` as the primary local source for the
  ecosystem description, principles, terminology, status, and boundaries.
- Use the owning repository for implementation claims and repository-specific
  descriptions.
- Use root `../.instructions/` for portfolio coordination and global safety
  boundaries.

## Public communication

- Write public organization content in clear English.
- Distinguish governed documentation, research, prototypes, test environments,
  active implementations, and production systems.
- Do not publish guaranteed returns, investment promises, fabricated metrics,
  unverified partnerships, or unsupported production claims.
- Keep repository links aligned with the actual `Axodus` organization remotes.
- Keep `profile/README.md` concise enough to work as the organization landing
  page and direct detailed readers to `Axodus/Documentation`.

## Repository boundaries

- Do not add product code, contracts, deployment scripts, package managers, or
  domain runtime configuration to this repository.
- Organization workflows may validate profile and community files, but must not
  deploy contracts, move funds, use wallet keys, or execute product releases.
- Changes to a nucleus belong in that nucleus repository and follow its local
  instructions.

## Validation

Before completing a change:

1. run `git diff --check`;
2. verify that `profile/README.md` exists and is not empty;
3. verify every listed repository against its local `origin` when available;
4. inspect public text for unsupported maturity, financial, partnership, or
   execution claims.
