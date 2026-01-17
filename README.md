# EDR-Driven Threat Hunting

## Objective

This repository focuses on detection-driven threat hunting
using endpoint and EDR telemetry.

The goal is to identify lateral movement, credential abuse,
and post-exploitation activity by correlating endpoint behaviors
rather than relying on single alerts.

## Scope

The project emphasizes:
- Process execution telemetry
- Parent-child process relationships
- Authentication and remote execution artifacts
- Lateral movement precursors

This repository is intentionally separated from
identity-based detections to maintain clear domain boundaries.
