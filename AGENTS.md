# Lazurio Example Organization infra-example: instructions for agents

Since 2026-11-14 this public repository is `infra-example`, public
documentation and an example only. Nothing here is authoritative.

## Source of truth

The Organization's authoritative access records are in its private `infra`
repository (`LazurioExampleOrganization/infra`, `access/`), the Deployment
Repo that the root's `modules.manifest.json` slot `infra` and
`company.gen3.json` (`infra/access`) name. Propose and record access changes
there, not here.

Until the rename on 2026-11-14 the records in this repository were the
authoritative ones. The `access/` documents here are a public copy as of commit
`06ca1a2` and are not kept current.

## Rules

- Do not write secrets, tokens, OAuth session data or private keys.
- Make external changes in GitHub, the cloud, DNS or billing accounts only on
  explicit instruction.
- When you document the state of an external service, write the date of
  verification and the source of the finding.
- Describe access changes concretely: who, to what, why and how it will be
  audited.

## Before the rename (historical)

The GitHub Organization `LazurioExampleOrganization` holds the repositories of
Lazurio Example Organization. Until 2026-11-14 its verified access state was
recorded in `access/github-organization.md` of this repository; the current
record is in the private `infra`.
