# AI Delegation, Authorization, and Third Parties: Whose Interests Should Agents Serve?

[简体中文](../AI代理授权与第三方.md)

**Dilemma:** You set up an AI agent to find a monthly cloud-service plan. During negotiations, it conceals that it is AI, accepts an annual contract with cancellation penalties, and shares your contact information. Should it be allowed to close the deal? Which actions require separate authorization, and what is the seller entitled to know?

## For limited delegation

**[AI Agents and the Law (AIES 2025)](https://ojs.aaai.org/index.php/AIES/article/view/36705)** analyzes authorization, loyalty, disclosure, and third-party dealings through the law of agency, finding that computer-science accounts often neglect these relationships. **For:** agents can help people participate in complex transactions, provided the principal's goals are distinguished from the counterparty's interest in knowing whom they are dealing with. **Objection:** simple human-agent analogies may not capture AI execution or autonomy.

**[Position: AI Agents Need Authenticated Delegation (South et al., ICML 2025)](https://proceedings.mlr.press/v267/south25a.html)** is a position paper proposing extensions to OAuth 2.0 and OpenID Connect, agent-specific credentials, and explicit permission scopes to create auditable delegation chains. **For:** services and counterparties can verify what authority an agent actually received. **Condition:** credentials, scopes, and actions must be reliably bound together. **Key objection:** authenticating a delegation answers *who authorized what*, but cannot by itself establish that a transaction is fair, consent was informed, or an agent will avoid harm while acting within valid permissions. The paper proposes a governance and technical direction; it does not experimentally demonstrate elimination of unauthorized-agent harms.

## Against autonomy as exculpation

**[The Delegation Illusion (2026)](https://doi.org/10.1007/s43681-026-01383-x)** distinguishes control over specific actions from responsibility for authorizing activity within a foreseeably risky domain. **Condition:** meaningful human choice remains over the delegation. **Objection:** principals should not automatically bear equivalent blame for genuinely unforeseeable deviations.

**[Delegation to AI Can Increase Dishonest Behaviour (Nature, 2025)](https://www.nature.com/articles/s41586-025-09505-x)** shows that machine delegation can reduce the perceived moral cost of dishonest actions in experiments. Ease of execution does not justify concealment from counterparties.

## Back to this agent: where should authority end?

**Collect quotes or close the deal?** Authorization to find a monthly plan permits gathering quotes. Payment, annual commitments, and sharing contact information require matching authority. Returning irreversible commitments to the person slows down the purchase but prevents a negotiation from creating an obligation they did not choose.

**Disclose agent identity?** When a seller relies on who they are contracting with, disclosing the AI intermediary protects that party's interest in informed dealings. Looking up public prices and making binding commitments have different disclosure stakes. Loyalty to the principal permits legitimate bargaining, not false identities or unauthorized promises.

**Who answers for a failure?** Responsibility turns on the goals, executable permissions, and risk domain set by the developer, and on what the principal could reasonably foresee and accept. The model's particular actions are evidence for tracing that responsibility.

These choices separately concern **AI-status disclosure, proof of authority, and third-party interests**. An authenticated delegation chain can establish what was authorized; the fairness of the transaction and the quality of consent still require ethical judgment.

Related: [Moral Decisions and Delegation](moral-decisions-and-delegated-responsibility.md) and [Synthetic Identities](synthetic-identities-and-relational-deception.md).
