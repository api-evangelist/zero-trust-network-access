# Zero Trust Network Access (zero-trust-network-access)

Zero Trust Network Access (ZTNA) is a security framework and product category that grants access to private applications and resources based on identity, device posture, and context, rather than network location. ZTNA replaces the implicit trust of legacy VPNs with explicit per-request verification, creating one-to-one encrypted tunnels between authenticated users and the specific applications they are authorized to use. This topic collects the leading ZTNA vendors, the standards bodies that govern the underlying primitives, and the data schemas used to describe access policies, identities, devices, and resources.

**URL:** [https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/](https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/)

## Tags

- Access Control, Cloud Security, Cybersecurity, Identity Management, Network Access, Network Security, Security, VPN Replacement, Zero Trust, ZTNA

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### Cloudflare Zero Trust API

Cloudflare Zero Trust provides ZTNA, secure web gateway, browser isolation, CASB, and DLP through a single global edge platform.

- [Documentation](https://developers.cloudflare.com/cloudflare-one/)
- [APIReference](https://developers.cloudflare.com/api/)

### Zscaler Private Access (ZPA) API

Zscaler Private Access is a cloud-native ZTNA service that connects authenticated users to private applications without exposing them to the internet.

- [Documentation](https://help.zscaler.com/zpa)
- [APIReference](https://help.zscaler.com/zpa/api-reference)

### Netskope Private Access API

Netskope Private Access provides ZTNA as part of the Netskope SASE platform, brokering authenticated access to private applications across cloud and on-premises.

- [Documentation](https://docs.netskope.com/en/netskope-help/admin-console/rest-api/)

### Palo Alto Prisma Access (Prisma SASE) API

Palo Alto Networks Prisma Access offers cloud-delivered ZTNA, SWG, and FWaaS as part of the Prisma SASE platform.

- [Documentation](https://docs.paloaltonetworks.com/prisma/prisma-access)

### Tailscale API

Tailscale is a WireGuard-based mesh-VPN ZTNA platform that exposes a REST API for managing devices, ACL policies, tailnet keys, DNS, and audit logs.

- [Documentation](https://tailscale.com/api)
- [APIReference](https://tailscale.com/api)
- [GitHub](https://github.com/tailscale)

### Twingate API

Twingate is a software-defined ZTNA platform that exposes a GraphQL Admin API for managing remote networks, resources, groups, users, service accounts, and connectors.

- [Documentation](https://www.twingate.com/docs/api)

## Common Properties

- [Cloudflare - What Is Zero Trust](https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/)
- [Gartner Definition of ZTNA](https://www.gartner.com/en/information-technology/glossary/zero-trust-network-access-ztna-)
- [NIST SP 800-207](https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf)
- [CISA Zero Trust Maturity Model](https://www.cisa.gov/zero-trust-maturity-model)
- [Cloudflare Zero Trust](https://www.cloudflare.com/zero-trust/)
- [Zscaler Zero Trust Exchange](https://www.zscaler.com/products-and-solutions/zero-trust-exchange)
- [Netskope SASE](https://www.netskope.com/platform/sase)
- [Palo Alto Networks Prisma Access](https://www.paloaltonetworks.com/sase/access)
- [Tailscale](https://tailscale.com/)
- [Twingate](https://www.twingate.com/)

## Artifacts

### JSON Schema

- [ZTNA Access Policy Schema](json-schema/zero-trust-network-access-policy-schema.json)
- [ZTNA Application Schema](json-schema/zero-trust-network-access-application-schema.json)
- [ZTNA Device Posture Schema](json-schema/zero-trust-network-access-device-posture-schema.json)

### JSON Structure

- [ZTNA Access Policy Structure](json-structure/zero-trust-network-access-policy-structure.json)

### JSON-LD

- [ZTNA JSON-LD Context](json-ld/zero-trust-network-access-context.jsonld)

### Examples

- [ZTNA Access Policy Example](examples/zero-trust-network-access-policy-example.json)
- [ZTNA Device Posture Example](examples/zero-trust-network-access-device-posture-example.json)

## Vocabulary

- [ZTNA Vocabulary](vocabulary/zero-trust-network-access-vocabulary.yaml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
