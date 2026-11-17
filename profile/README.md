## Auditail

**Get your money-moving AI agent to production.**

Your risk team, sponsor bank or biggest customer won't let an AI agent touch payouts or refunds without hard limits and an audit trail. Auditail is that layer:

- **Limits the agent can't change**, counted on our server, so splitting a payment doesn't get around a cap. Shared caps across card, wire and refund rails.
- **A person on the risky payments**, approved in the dashboard or Slack. Two-person approval and approvers' own signatures when you require them.
- **Every payment matched to what settled**: Stripe Issuing captures, Airwallex and Modern Treasury events, bank statement lines. Mismatches and missing settlements alert you, and can freeze the agent.
- **Built for agents:** session taint after the agent reads an email or a web page, an MCP proxy, and pause/resume for Temporal, Inngest and LangGraph.

**Your launch week:** run `npx -p auditail-sdk auditail init` on Monday (shadow mode, nothing blocked). Get the drift report in Slack during the week. Hand your reviewers a signed [risk pack](https://auditail.io/samples/auditail-sample-risk-pack.html) on Friday. Then flip to enforce.

*Gateways see the tool call. Auditail follows the money.*

- **Website:** [auditail.io](https://auditail.io) · **Docs:** [auditail.io/docs](https://auditail.io/docs) · **Teardowns:** [auditail.io/docs/teardowns](https://auditail.io/docs/teardowns/prompt-injected-refund) · **Security:** [auditail.io/docs/security](https://auditail.io/docs/security)
- **SDKs:** [`auditail-sdk`](https://www.npmjs.com/package/auditail-sdk) (TypeScript) · [`auditail`](https://pypi.org/project/auditail/) (Python)
- **Verify without trusting us:** the SDKs, the offline verifier, the MCP proxy and the [examples](https://github.com/auditailhq/auditail-sdk/tree/main/examples) are [open source (MIT)](https://github.com/auditailhq/auditail-sdk). Everything Auditail signs checks out offline.

Private beta, working with design partners in payments, lending and neobanking. Contact: [hello@auditail.io](mailto:hello@auditail.io)
