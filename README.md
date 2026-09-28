# zetaflow

An open-source runbook execution engine that turns existing Markdown SOPs into controlled, executable workflows. A locally hosted open-weight LLM interprets the runbook into structured steps, while a policy-controlled executor runs commands, APIs, and checks, pausing for human approval at high risk decisions. Every execution produces a trace that is compared against the original runbook to detect skipped, reordered, modified, or undocumented steps helping teams automatically identify and fix runbook drift.
