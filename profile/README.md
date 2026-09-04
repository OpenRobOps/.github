# OpenRobOps

**Open-source robot fleet management and operations.**

OpenRobOps (ORO) is an open-source robot fleet management and operations platform.
It provides real-time observability, monitoring, and control for autonomous mobile 
robots (AMRs) — fully self-hostable, with native support for ROS, Open RMF 
and the ISO 21423 robot interoperability standard.

It was started by [InOrbit.AI](https://www.inorbit.ai), bringing
the technology used in production to manage thousands of robots into an open
foundation that teams can own and extend.

🌐 **[openrobops.org](https://openrobops.org)** · 📦 **[OpenRobOps/oro](https://github.com/OpenRobOps/oro)** · 📄 Apache 2.0

## Why OpenRobOps

- **Real-time fleet observability** — live telemetry, maps, cameras, diagnostics and customizable dashboards.
- **Vendor-agnostic** — one MQTT-based messaging layer for robots from any manufacturer.
- **Standards-native** — speaks ISO 21423 out of the box; integrates with ROS 2 and Open RMF.
- **Self-hosted and extensible** — run it anywhere with Docker Compose; extend it with pluggable ingest modules.

## Get started

Everything begins in the main repository: **[OpenRobOps/oro](https://github.com/OpenRobOps/oro)**.
Its README covers the architecture, a quick start with Docker Compose, and
how to connect your first robot. Prefer to try it without hardware? Spin up
the [Flatland simulator](https://github.com/OpenRobOps/sim-flatland) and
point it at your ORO instance.

## Repositories

| Repository | What it is |
|---|---|
| [**oro**](https://github.com/OpenRobOps/oro) | **The OpenRobOps platform** — web app, ingest service, MQTT broker and configuration tooling. Start here. |
| [iso21423](https://github.com/OpenRobOps/iso21423) | ISO 21423 (mobile robot interoperability) SDKs and reference material, including the `@openrobops/iso21423` TypeScript SDK. |
| [sim-flatland](https://github.com/OpenRobOps/sim-flatland) | Lightweight 2D ROS 2 / Nav2 simulated robot for developing and testing against ORO without hardware. |
| [openrmf-oro-adapter](https://github.com/OpenRobOps/openrmf-oro-adapter) | Open RMF fleet adapter for OpenRobOps. |
| [openrmf-oro-demo](https://github.com/OpenRobOps/openrmf-oro-demo) | Demo of OpenRobOps with the Open RMF adapter. |
| [mosquitto-go-auth](https://github.com/OpenRobOps/mosquitto-go-auth) | Fork of the Mosquitto auth plugin used by ORO's broker (patched MongoDB driver). |

## Community

- **Website & docs:** [openrobops.org](https://openrobops.org)
- **Issues & discussions:** open them in the relevant repository, primarily [oro](https://github.com/OpenRobOps/oro/issues).
- **Contributing:** see [CONTRIBUTING.md](https://github.com/OpenRobOps/oro/blob/main/CONTRIBUTING.md) in the main repo.

OpenRobOps is licensed under the [Apache License 2.0](https://github.com/OpenRobOps/oro/blob/main/LICENSE).
