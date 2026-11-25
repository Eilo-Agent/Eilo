# Tool Registry

This file defines how to document tools; it does not assert that any particular tool is installed.

For each runtime tool record:
- Name and provider.
- Purpose and supported operations.
- Input/output schema and version.
- Authentication method and required scopes.
- Data sent/received and retention implications.
- Rate limits, costs, and failure modes.
- Approval requirements and destructive effects.
- Test procedure and last verified date.

A tool is available only when the host exposes it in the current session. Verify capability at runtime; never infer access from documentation.
