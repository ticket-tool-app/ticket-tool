# Security Policy

Ticket Tool runs as a hosted service, so the only version we support is the one
currently live at `ticket-tool.app`, `dash.ticket-tool.app` and
`api.ticket-tool.app`.

## Reporting a vulnerability

Report it privately rather than opening a public issue. Either:

- Use the **Report a vulnerability** button on the
  [Security tab](https://github.com/Ticket-Tool-App/ticket-tool/security), or
- Email [support@ticket-tool.app](mailto:support@ticket-tool.app) with
  `SECURITY` in the subject.

Tell us what the problem is, which part it affects (bot, dashboard, API, or a
public knowledge base portal) and how to reproduce it. A proof of concept helps.
So does anything that lets us find it in our logs: server IDs, ticket IDs,
request IDs, a rough timestamp.

## What to expect

We'll acknowledge inside 3 business days and come back with an assessment within
a week. After that you'll get a timeline, though anything critical jumps the
queue. We'll tell you when the fix is live, and we're happy to credit you by
name if you want that.

## Scope

Covered: `ticket-tool.app`, `dash.ticket-tool.app`, `api.ticket-tool.app`, the
hosted knowledge base portals, and the Discord bot and its commands.

Not covered:

- Denial of service, volumetric or load testing
- Social engineering of our staff, our customers, or their members
- Anything that only affects a server you don't own or have permission to test in
- Raw scanner output, missing hardening headers, and similar best-practice
  findings with nothing exploitable behind them

## Testing

Only test against servers and accounts you control. Don't read, change or keep
other customers' tickets, transcripts or personal data. If you stumble into any,
stop there and mention it in your report.

We don't run a paid bounty. We won't come after anyone who follows this policy
in good faith.
