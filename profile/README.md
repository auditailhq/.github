## Auditail

**Controls and evidence for AI agents that move money.**

Auditail checks every action an AI agent takes against a policy the agent can't change: spending limits, new-payee rules, human and two-person approval, and a kill switch. It records each decision in a signed, tamper-evident log that anyone can verify offline.

- **Website:** [auditail.io](https://auditail.io) · **Docs:** [auditail.io/docs](https://auditail.io/docs) · **Security:** [auditail.io/docs/security](https://auditail.io/docs/security)
- **SDKs:** [`auditail-sdk`](https://www.npmjs.com/package/auditail-sdk) (TypeScript) · [`auditail`](https://pypi.org/project/auditail/) (Python)
- **Works with:** Stripe Issuing, Airwallex and Modern Treasury, or any agent framework (OpenAI Agents SDK, LangChain)
- **Verify without trusting us:** the SDKs, the offline verifier and the MCP proxy are [open source (MIT)](https://github.com/auditailhq/auditail-sdk); everything Auditail signs checks out offline

Private beta, working with design partners in payments, lending and neobanking. Contact: [hello@auditail.io](mailto:hello@auditail.io)
