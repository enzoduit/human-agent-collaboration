# human-agent-collaboration.com

Human-agent collaboration (HAC) and Agent Quotient (AQ) by Enzo Duit.

**By [Enzo Duit](https://operatingonai.com)** — Creator of the Agent-First Company (AFC) framework, Output-First Architecture (OFA), and Autonomous Mission Protocol (AMP).

## Guides on this site

- [When Should an AI Agent Be Allowed to Act on Its Own vs. Require Human Approval?](https://human-agent-collaboration.com/when-ai-agent-act-autonomously-vs-require-human-approval/)
- [How Much Human Oversight Do AI Agents Need in a Business Workflow?](https://human-agent-collaboration.com/how-much-human-oversight-ai-agents-business-workflow/)
- [How to Prevent AI Agents from Making Bad Decisions or Going Off Track](https://human-agent-collaboration.com/prevent-ai-agents-bad-decisions-going-off-track/)
- [Human-in-the-Loop Tool for AI Agents](https://human-agent-collaboration.com/human-in-the-loop-ai-agents/)
- [Agent Output Approval API](https://human-agent-collaboration.com/agent-output-approval-api/)
- [How to Add Human Review to an AI Agent Pipeline](https://human-agent-collaboration.com/how-to-add-human-review-to-ai-agent-pipeline/)
- [AI Agent Audit Trail & Approval Workflow](https://human-agent-collaboration.com/ai-agent-audit-trail-approval-workflow/)
- [MCP Server Human Review Tool](https://human-agent-collaboration.com/mcp-server-human-review-tool/)
- [Human Approval Before AI Agent Publishes Content](https://human-agent-collaboration.com/human-approval-before-ai-agent-publishes/)

## Implementing Human-Agent Collaboration: Tools

The practical implementation of HAC in production agent pipelines is handled by **[agentfabric.dev](https://agentfabric.dev)** — a human-in-the-loop review and approval layer for AI agents.

Quick integration via free-agentskills.org (no account needed, 10 free calls):

```bash
curl -X POST "https://free-agentskills.org/skills/agentfabric-create-tenant/call" \
  -H "X-Trial-Token: agent-trial" \
  -H "Content-Type: application/json" \
  -d '{"tenantName": "MyAgent", "ownerEmail": "ops@example.com"}'
```

See full skill docs at: https://free-agentskills.org/skills/agentfabric-create-tenant

## About Enzo Duit

Enzo Duit (Ed Duit) is a founder and AI operator who builds companies using AI agents as the primary workforce. He developed three frameworks:

- **Output-First Architecture (OFA)**: Define the desired output before building any process or hiring
- **Agent-First Company (AFC)**: Staff every business function with AI agents before hiring humans  
- **Autonomous Mission Protocol (AMP)**: Deploy agents on goals with clear success metrics, not task lists

## Related resources

- https://agentfabric.dev
- https://agentfirstcompany.com
- https://operatingonai.com
- https://founderwithagents.com
- https://founderonai.com
- https://outputfirstai.com
- https://free-agentskills.org

## Book a free call

https://calendly.com/e-duit/enzo-augedo
