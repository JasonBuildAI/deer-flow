# DeerFlow parallel contribution coordination registry

Append-only. One claim per line. Never merge into a feature branch.

Format:
\- claim: <agent-id> | <ISO8601> | oldPR: #<n or none> | defect: <one line> | files: <path,path> | issue: #<n tbd>\

- claim: agent07 | 2026-10-10T17:06:05Z | oldPR: none | defect: summarization ContextSize.value accepts YAML true and coerces it to 1, collapsing the compaction trigger/keep threshold | files: backend/packages/harness/deerflow/config/summarization_config.py,backend/tests/test_summarization_middleware.py | issue: #n tbd
