# Documentation and Contribution Rules

[简体中文](AGENTS.zh-CN.md)

## First rule: writing failures to eliminate

**Keep facts, arguments, and evidential limits that change interpretation. Fix the following problems in the text itself; never compensate with additional explanations:**

- **Defensive filler:** Repeated “does not prove / does not mean” rebuttals to extreme claims nobody made, or closing disclaimers already covered in the argument. State a material objection or scope limit once, alongside the claim it qualifies.
- **Artificial balance and empty conclusions:** Inventing positions or equal-length sections to fill a for/against/conditional template, or ending with “consider all factors” instead of a judgment. Let actual disagreements and evidential weight determine sections, headings, and conclusions; merge or delete conditional sections without independent reasoning.
- **Evidence substitution:** Turning interviews, attitude ratings, short-term intentions, or correlations into population rates, long-term outcomes, or causal effects; treating a normative proposal as an empirical finding or attributing an editor's inference to an author. Report what a study actually measured and found.
- **One study, multiple homes:** Repeating a study's design, sample, and results across topics or restating the same principle in multiple endings. Keep one full summary in its most relevant topic; elsewhere add only the topic-specific inference and a link.
- **Damage during cleanup:** Losing unique facts, sources, or navigation; leaving truncated conclusions, orphaned labels, or empty sections; or causing Chinese and English arguments, numbers, or scope to diverge. Reread the affected paragraphs and complete pages; check sources, relative links, and both languages.
- **Editorial residue:** Deletion is final. Leave no “removed” notices, instructions not to write something here, review notes, deprecated stubs, placeholders, or explanations of deleted text.

Before editing, read the [README](README.md) and [topic index](docs/domain/en/README.md). The Chinese topic pages in [docs/domain/](docs/domain/README.md) are the content source; the English translations are in [docs/domain/en/](docs/domain/en/README.md).

## Scope

The primary reader is an individual developer confronting a real ethical choice while using or building AI. Cover AI's possible interests, effects on others, consent, moral status, rights, duties, and relationships. Engineering implementation, collaboration efficiency, and system reliability belong in technical documentation.

## Writing

1. Start with a choice facing an individual developer: what they are doing with AI, who is affected, and the costs of feasible options. Then organize sourced arguments and substantive objections by evidential strength.
2. For each argument, give the author, central reasoning, conditions, key objections, and original source.
3. For empirical work, state the study design, population, findings, and limitations relevant to interpretation. Keep empirical findings separate from normative positions.
4. Give each full research summary one topic home; link to it from other topics. Indexes provide navigation.
5. Update existing topics before adding new ones; replace outdated material and delete superseded material.
6. Keep Chinese and English counterparts aligned in the same change. Translate claims and sources faithfully; use links between corresponding pages.

## Navigation and Checks

- [English reading index](docs/README.md) · [Chinese reading index](docs/README.zh-CN.md)
- [English topics](docs/domain/en/README.md) · [Chinese topics](docs/domain/README.md)
- Add Chinese topics under `docs/domain/` and English equivalents with kebab-case names under `docs/domain/en/`; update both indexes.
- Check source claims, numbers, translation consistency, and relative links. Commit to `main`.
