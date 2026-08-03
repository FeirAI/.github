# FeirAI

**The operating system for accountable agent organizations.**

FeirAI builds governance infrastructure for autonomous operations: policy before an action runs, bounded credentials and budgets while it runs, and offline-verifiable evidence afterward.

## FeirOS

[FeirOS](https://feir.ai) is the flagship product — a governed action boundary between AI agents and sensitive systems.

For every action routed through it, FeirOS:

1. **Authorizes** against explicit policy and approvals (decide)
2. **Enforces** with short-lived scoped credentials agents never see (enforce)
3. **Meters** consumption against budgets with honest, bounded overshoot (meter)
4. **Proves** with signed, tamper-evident records that verify offline (prove)

Authorize before. Bound during. Prove after.

## Open-source planes

FeirOS is composed of four independently usable planes. Each will live in this organization as it is released:

| Plane | Role |
| --- | --- |
| **govder** | Decides — resolves policy into an effective config |
| **vultrino** | Enforces — in-path credential proxy; default-deny |
| **leria** | Meters — durable book of consumption and budgets |
| **averin** | Proves — signed, hash-chained, offline-verifiable flight recorder |

Claims stay bounded: evidence carries declared trust levels; metering admits bounded overshoot; only actions on the governed path are covered.

## Links

- Website: [feir.ai](https://feir.ai)
- Live demo: [demo.feir.ai](https://demo.feir.ai)
- LinkedIn: [company/feirai](https://www.linkedin.com/company/feirai/)

## Contact

Security reports: **security@feir.ai**  
General: [feir.ai](https://feir.ai)
