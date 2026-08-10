---
description: Run the channel-auditor subagent over agent_reach/channels/ and report contract/doc-drift findings
---

Dispatch to the `channel-auditor` subagent to audit `agent_reach/channels/*.py`.

If the user passed an argument (a channel name, e.g. `/audit-channels reddit`),
scope the audit to that one channel's file plus its registry entry and tests;
otherwise audit every channel.

Arguments: $ARGUMENTS
