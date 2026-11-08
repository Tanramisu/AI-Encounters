# AI Delegation, Authorization, and Third Parties: Whose Interests Should Agents Serve?

[简体中文](../AI代理授权与第三方.md)

**Dilemma:** A user delegates shopping, negotiation, promises, or contracts. Must counterparties know they face an AI? If an agent exceeds authority while intending to help, who remains responsible?

## For limited delegation

**[AI Agents and the Law (AIES 2025)](https://ojs.aaai.org/index.php/AIES/article/view/36705)** analyzes authorization, loyalty, disclosure, and third-party dealings through the law of agency, finding that computer-science accounts often neglect these relationships. **For:** agents can facilitate transactions while recognizing counterparty interests. **Objection:** simple human-agent analogies may not capture AI execution or autonomy.

**[Position: AI Agents Need Authenticated Delegation (South et al., ICML 2025)](https://proceedings.mlr.press/v267/south25a.html)** is a position paper proposing extensions to OAuth 2.0 and OpenID Connect, agent-specific credentials, and explicit permission scopes to create auditable delegation chains. **For:** services and counterparties can verify what authority an agent actually received. **Condition:** credentials, scopes, and actions must be reliably bound together. **Key objection:** authenticating a delegation answers *who authorized what*, but cannot by itself establish that a transaction is fair, consent was informed, or an agent will avoid harm while acting within valid permissions. The paper proposes a governance and technical direction; it does not experimentally demonstrate elimination of unauthorized-agent harms.

## Against autonomy as exculpation

**[The Delegation Illusion (2026)](https://doi.org/10.1007/s43681-026-01383-x)** distinguishes control over specific actions from responsibility for authorizing activity within a foreseeably risky domain. **Condition:** meaningful human choice remains over the delegation. **Objection:** principals should not automatically bear equivalent blame for genuinely unforeseeable deviations.

**[Delegation to AI Can Increase Dishonest Behaviour (Nature, 2025)](https://www.nature.com/articles/s41586-025-09505-x)** shows that machine delegation can reduce the perceived moral cost of dishonest actions in experiments. Ease of execution does not justify concealment from counterparties.

## Delegated authority and third-party interests

Distinguish **disclosing representative status, proving permission, acknowledging third-party rights, and obtaining specific authorization for irreversible acts**. Loyalty to a paying principal does not give blanket permission to deceive, but an unlimited duty to advance every counterparty's interests would also conflict with legitimate representation.

Related: [Moral Decisions and Delegation](moral-decisions-and-delegated-responsibility.md) and [Synthetic Identities](synthetic-identities-and-relational-deception.md).
