# Zero Trust Network Access (zero-trust-network-access)

Zero Trust Network Access (ZTNA) is a security framework and product category that grants access to private applications and resources based on identity, device posture, and context, rather than network location. ZTNA replaces the implicit trust of legacy VPNs with explicit per-request verification, creating one-to-one encrypted tunnels between authenticated users and the specific applications they are authorized to use. This topic collects the leading ZTNA vendors, the standards bodies that govern the underlying primitives, and the data schemas used to describe access policies, identities, devices, and resources.

**APIs.json:** [https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/](https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/)

## Scope

- **Type:** Index

## Tags

- Access Control
- Cloud Security
- Cybersecurity
- Identity Management
- Network Access
- Network Security
- Security
- VPN Replacement
- Zero Trust
- ZTNA

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### Cloudflare Zero Trust API

Cloudflare Zero Trust (formerly Cloudflare for Teams / Cloudflare Access) provides ZTNA, secure web gateway, browser isolation, CASB, and DLP through a single global edge platform. The Cloudflare API exposes endpoints for managing Access applications, policies, identity providers, device posture, tunnels, and gateway rules.

- **Human URL:** [https://developers.cloudflare.com/cloudflare-one/](https://developers.cloudflare.com/cloudflare-one/)

#### Tags

- Cloudflare
- SASE
- ZTNA

#### Properties

- [Documentation](https://developers.cloudflare.com/cloudflare-one/)
- [API Reference](https://developers.cloudflare.com/api/)
- [Authentication](https://developers.cloudflare.com/fundamentals/api/get-started/keys/)

### Zscaler Private Access (ZPA) API

Zscaler Private Access is a cloud-native ZTNA service that connects authenticated users to private applications without exposing them to the internet or placing them on the corporate network. The ZPA Public API supports application segments, server groups, policies, posture profiles, and connector groups.

- **Human URL:** [https://help.zscaler.com/zpa/api-reference](https://help.zscaler.com/zpa/api-reference)

#### Tags

- SASE
- Zscaler
- ZTNA

#### Properties

- [Documentation](https://help.zscaler.com/zpa)
- [API Reference](https://help.zscaler.com/zpa/api-reference)

### Netskope Private Access API

Netskope Private Access provides ZTNA as part of the Netskope SASE platform, brokering authenticated access to private applications across cloud and on-premises. The Netskope REST API surfaces operations on private apps, publishers, policies, and risk events.

- **Human URL:** [https://docs.netskope.com/en/netskope-help/admin-console/rest-api/](https://docs.netskope.com/en/netskope-help/admin-console/rest-api/)

#### Tags

- Netskope
- SASE
- ZTNA

#### Properties

- [Documentation](https://docs.netskope.com/en/netskope-help/admin-console/rest-api/)

### Palo Alto Prisma Access (Prisma SASE) API

Palo Alto Networks Prisma Access offers cloud-delivered ZTNA, SWG, and FWaaS as part of the Prisma SASE platform. The Prisma Access REST API exposes operations on remote networks, mobile users, security policies, and decryption rules.

- **Human URL:** [https://docs.paloaltonetworks.com/prisma/prisma-access](https://docs.paloaltonetworks.com/prisma/prisma-access)

#### Tags

- Palo Alto
- SASE
- ZTNA

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/prisma/prisma-access)

### Tailscale API

Tailscale is a WireGuard-based mesh-VPN ZTNA platform that exposes a REST API for managing devices, ACL policies, tailnet keys, DNS, and audit logs. It implements identity-based device-to-device tunnels brokered by an identity-aware control plane.

- **Human URL:** [https://tailscale.com/api](https://tailscale.com/api)

#### Tags

- Mesh VPN
- Tailscale
- WireGuard
- ZTNA

#### Properties

- [Documentation](https://tailscale.com/api)
- [API Reference](https://tailscale.com/api)
- [GitHub Organization](https://github.com/tailscale)

### Twingate API

Twingate is a software-defined ZTNA platform that exposes a GraphQL Admin API for managing remote networks, resources, groups, users, service accounts, and connectors.

- **Human URL:** [https://www.twingate.com/docs/api](https://www.twingate.com/docs/api)

#### Tags

- Twingate
- ZTNA

#### Properties

- [Documentation](https://www.twingate.com/docs/api)
- [API Reference](https://www.twingate.com/docs/api)

## Common Properties

- [Documentation](https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/)
- [Documentation](https://www.gartner.com/en/information-technology/glossary/zero-trust-network-access-ztna-)
- [Documentation](https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf)
- [Compliance](https://www.cisa.gov/zero-trust-maturity-model)
- [Portal](https://www.cloudflare.com/zero-trust/)
- [Portal](https://www.zscaler.com/products-and-solutions/zero-trust-exchange)
- [Portal](https://www.netskope.com/platform/sase)
- [Portal](https://www.paloaltonetworks.com/sase/access)
- [Portal](https://tailscale.com/)
- [Portal](https://www.twingate.com/)
- [GitHub Organization](https://github.com/tailscale)
- [GitHub Organization](https://github.com/WireGuard)
- [JSON Schema](json-schema/zero-trust-network-access-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zero-trust-network-access-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zero-trust-network-access-device-posture-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/zero-trust-network-access-policy-structure.json)
- [JSON-LD](json-ld/zero-trust-network-access-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Code Examples](examples/zero-trust-network-access-policy-example.json)
- [Code Examples](examples/zero-trust-network-access-device-posture-example.json)
- [Resources](vocabulary/zero-trust-network-access-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://www.cloudflare.com/partners/technology-partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
