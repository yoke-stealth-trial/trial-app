# Test Inventory: STEALTH trial App

Yoke command definitions in the authoritative DB own executable test command
records. This file explains how agents and operators should interpret those
surfaces for STEALTH trial App.

## Scopes

- `quick` - focused checks for the changed surface.
- `full` - broader local verification before review or merge.
- `smoke` - deployed-target health checks when the project has a deploy flow.
- `e2e` - deployed-system verification when a real E2E suite exists.

Update this file when test intent changes. Update DB command definitions when
the executable commands change.
