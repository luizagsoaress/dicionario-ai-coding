---
descrição: An isolated environment the agente runs inside — container, VM, or restricted shell. Limits the blast radius of agente actions.
aliases:
  - Sandboxing
  - Sandbox / Sandboxing
---
An isolated [environment](./Environment.md) the [agente](./agente.md) runs inside — a container, VM, ephemeral [filesystem](./Filesystem.md), or restricted-permission shell. Limits the blast radius of agente actions: even if the agente runs destructive commands or fetches something malicious, the damage is contained. The safety substrate that makes [AFK](./AFK.md) practical.

*Uso:*

"I want to let it run [bypass-permissions](./agente%20mode.md) overnight but I'm not ready for that."

"Put it in a sandbox — fresh container, no credentials mounted, no network out. Worst case it nukes its own filesystem and you discard the container."
