# TRACE / GO2 Architecture

This document describes a future research direction. It does not claim that TRACE Runtime and GO2 are already integrated.

## Architecture Direction

```text
Human operator
  ->
AI Agent Workflow
  ->
Function Calling / Structured Output
  ->
Robot command schema
  ->
Safety and approval boundary
  ->
ROS2 adapter
  ->
Unitree GO2 Air
```

## Design Principles

- Keep human approval visible before physical execution.
- Treat AI output as intent, not as direct hardware control.
- Validate commands against a typed schema.
- Separate high-level planning from low-level robot control.
- Log commands and outcomes for review.
- Keep private runtime and deployment details out of this public repository.

## Future TRACE Relationship

The long-term research direction is to explore how TRACE Agent workflows could coordinate robotics skills, command validation, and public demo artifacts.

This repository does not modify TRACE Runtime and does not claim completed TRACE / GO2 integration.

## Claim Boundary

No autonomous navigation, production robotics deployment, or finished ROS2 integration is claimed here.
