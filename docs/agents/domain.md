# Domain docs

## Read before working

- Read [DOMAIN.md](../../DOMAIN.md) for agreed domain terms.
- Read [docs/domain-model.md](../domain-model.md) for relationships, invariants, module responsibilities and interactions. Treat its open questions as unresolved.
- Read the relevant ADRs in `docs/adr/`. For permissions, read [ADR-0001](../adr/0001-platform-access-ownership.md); for access operations, read [ADR-0002](../adr/0002-access-change-orchestration.md).
- Use [docs/first-version.md](../first-version.md) to determine delivery scope. A concept in the model does not itself add a capability to the delivery.

## Use and maintain

- Use the glossary's vocabulary in discussion, code, issue titles and tests. Record agreed terms with the `domain-modeling` skill; keep `DOMAIN.md` a glossary.
- Record relationships, lifecycle rules and module responsibilities in `docs/domain-model.md`. Keep confirmed decisions and open questions separate.
- Record consequential architectural trade-offs in `docs/adr/`, including alternatives and reasons. Identify conflicts with accepted ADRs before proposing a revision.
- Keep one domain context: the root glossary, one domain model and repository-wide ADRs.
