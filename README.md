# Palo Alto Networks (palo-alto-networks)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Palo Alto Networks is a global cybersecurity leader providing advanced security platforms and services across network security, cloud security, and security operations. Its developer platform at pan.dev offers REST and XML APIs for PAN-OS firewalls, Strata Cloud Manager, Prisma Cloud (CSPM, CWPP, code security), Prisma Access and SD-WAN for SASE, Cortex XDR/XSOAR/XSIAM for security operations, and cloud-delivered security services including WildFire, Threat Vault, IoT Security, and DLP.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/apis.yml)

## Tags

- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### PAN-OS REST API

A RESTful API for managing PAN-OS next-generation firewalls including security policies, network objects, address groups, and device configuration. The REST API provides simplified JSON-based access to common firewall operations as an alternative to the XML API. Supports CRUD operations on policy rules, address objects, service objects, and security profiles. Authentication uses API keys generated from the firewall management interface or via the XML API keygen command.

- **Human URL:** [https://pan.dev/panos/docs/restapi/](https://pan.dev/panos/docs/restapi/)
- **Base URL:** `https://{firewall}/restapi/v10.2`

#### Tags

- Configuration
- Firewall
- Network Security
- Policies
- REST API

#### Properties

- [Documentation](https://pan.dev/panos/docs/restapi/)
- [Getting Started](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-rest-api)
- [API Reference](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/pan-os-rest-api-reference)
- [Authentication](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-rest-api/get-your-api-key)
- [OpenAPI](openapi/palo-alto-pan-os-rest-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/pan-os-rest-api-address-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-rest-api-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-rest-api-commit-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-rest-api-nat-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-rest-api-pan-os-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-rest-api-qos-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-rest-api-security-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-rest-api-service-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-rest-api-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-rest-api-tag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-rest-api-virtual-system-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pan-os-security-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/pan-os-rest-api-address-group-structure.json)
- [JSON Structure](json-structure/pan-os-rest-api-address-structure.json)
- [JSON Structure](json-structure/pan-os-rest-api-commit-status-structure.json)
- [JSON Structure](json-structure/pan-os-rest-api-nat-rule-structure.json)
- [JSON Structure](json-structure/pan-os-rest-api-pan-os-response-structure.json)
- [JSON Structure](json-structure/pan-os-rest-api-qos-rule-structure.json)
- [JSON Structure](json-structure/pan-os-rest-api-security-rule-structure.json)
- [JSON Structure](json-structure/pan-os-rest-api-service-group-structure.json)
- [JSON Structure](json-structure/pan-os-rest-api-service-structure.json)
- [JSON Structure](json-structure/pan-os-rest-api-tag-structure.json)
- [JSON Structure](json-structure/pan-os-rest-api-virtual-system-structure.json)
- [JSON Structure](json-structure/pan-os-security-rule-structure.json)
- [JSON-LD](json-ld/palo-alto-pan-os-rest-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/pan-os-rest-api-address-example.json)
- [Example](examples/pan-os-rest-api-address-group-example.json)
- [Example](examples/pan-os-rest-api-commit-status-example.json)
- [Example](examples/pan-os-rest-api-nat-rule-example.json)
- [Example](examples/pan-os-rest-api-pan-os-response-example.json)
- [Example](examples/pan-os-rest-api-qos-rule-example.json)
- [Example](examples/pan-os-rest-api-security-rule-example.json)
- [Example](examples/pan-os-rest-api-service-example.json)
- [Example](examples/pan-os-rest-api-service-group-example.json)
- [Example](examples/pan-os-rest-api-tag-example.json)
- [Example](examples/pan-os-rest-api-virtual-system-example.json)
- [Example](examples/pan-os-security-rule-example.json)
- [JSON-LD](json-ld/palo-alto-pan-os-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### PAN-OS XML API

The comprehensive XML-based API for PAN-OS providing full access to all firewall configuration, operational commands, reporting, logging, and commit operations. Supports request types including keygen for authentication, config for configuration changes using XPath, op for operational commands, report for generating reports, log for retrieving traffic and threat logs, and user-id for dynamic user-to-IP mapping.

- **Human URL:** [https://pan.dev/panos/docs/xmlapi/](https://pan.dev/panos/docs/xmlapi/)
- **Base URL:** `https://{firewall}/api/`

#### Tags

- Configuration
- Firewall
- Monitoring
- Operations
- XML

#### Properties

- [Documentation](https://pan.dev/panos/docs/xmlapi/)
- [Getting Started](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-xml-api)
- [API Reference](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/pan-os-xml-api-request-types)
- [Authentication](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-xml-api/get-your-api-key)
- [JSON Schema](json-schema/pan-os-security-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PAN-OS OpenConfig API

Management interface for PAN-OS based on OpenConfig standard data models, providing gNMI and gNOI services through the OpenConfig plugin. Supports network automation for BGP, interfaces, LACP, LLDP, VLANs, local routes, system, and platform configuration, as well as telemetry streaming. Includes a PAN-OS OpenConfig XML API for integration with standard network management tools.

- **Human URL:** [https://docs.paloaltonetworks.com/openconfig](https://docs.paloaltonetworks.com/openconfig)
- **Base URL:** `https://{firewall}`

#### Tags

- Firewall
- gNMI
- Network Automation
- OpenConfig
- Telemetry

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/openconfig)
- [Getting Started](https://docs.paloaltonetworks.com/openconfig/2-0/openconfig-admin/getting-started)
- [API Reference](https://docs.paloaltonetworks.com/openconfig/2-0/openconfig-admin/pan-os-models/pan-os-openconfig-xmlapi)
- [Postman Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Panorama API

The Panorama API uses the same PAN-OS XML and REST API interfaces but provides centralized management of multiple firewalls from a single management server. Supports device group and template stack operations for pushing configuration to managed firewalls, centralized logging and reporting, and multi-device commit workflows. Panorama-specific API operations include managing device groups, template stacks, log collectors, and performing push operations to managed devices.

- **Human URL:** [https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api)
- **Base URL:** `https://{panorama}/api/`

#### Tags

- Centralized Management
- Device Groups
- Firewall
- Orchestration
- Templates

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api)
- [API Reference](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api)
- [Postman Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Strata Cloud Manager API

A unified cloud-based API for managing Palo Alto Networks next-generation firewalls and SASE from a single management plane. Strata Cloud Manager provides configuration management for security policies, network objects, and device settings across hardware, virtual, and cloud-native firewalls. The API uses OAuth 2.0 authentication with bearer tokens and provides RESTful endpoints for policy lifecycle management, object CRUD operations, and deployment workflows.

- **Human URL:** [https://pan.dev/scm/docs/home/](https://pan.dev/scm/docs/home/)
- **Base URL:** `https://api.strata.paloaltonetworks.com`

#### Tags

- Cloud Management
- Configuration
- NGFW
- SASE
- Unified Management

#### Properties

- [Documentation](https://pan.dev/scm/docs/home/)
- [API Reference](https://pan.dev/scm/api/)
- [Getting Started](https://pan.dev/scm/docs/getstarted/)
- [Getting Started](https://pan.dev/scm/docs/api-call/)
- [Best Practices](https://pan.dev/scm/docs/api-best-practices/)
- [Changelog](https://pan.dev/scm/docs/release-notes/)
- [OpenAPI](openapi/palo-alto-strata-cloud-manager-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [SDK](https://github.com/PaloAltoNetworks/scm-go)
- [JSON Schema](json-schema/strata-cloud-manager-api-address-group-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-address-group-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-address-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-address-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-address-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-delete-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-nat-rule-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-nat-rule-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-nat-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-security-rule-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-security-rule-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-security-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-service-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-service-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-cloud-manager-api-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/strata-cloud-manager-api-address-group-list-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-address-group-request-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-address-group-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-address-list-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-address-request-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-address-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-delete-response-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-job-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-nat-rule-list-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-nat-rule-request-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-nat-rule-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-security-rule-list-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-security-rule-request-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-security-rule-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-service-list-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-service-request-structure.json)
- [JSON Structure](json-structure/strata-cloud-manager-api-service-structure.json)
- [JSON-LD](json-ld/palo-alto-strata-cloud-manager-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/strata-cloud-manager-api-address-example.json)
- [Example](examples/strata-cloud-manager-api-address-group-example.json)
- [Example](examples/strata-cloud-manager-api-address-group-list-example.json)
- [Example](examples/strata-cloud-manager-api-address-group-request-example.json)
- [Example](examples/strata-cloud-manager-api-address-list-example.json)
- [Example](examples/strata-cloud-manager-api-address-request-example.json)
- [Example](examples/strata-cloud-manager-api-delete-response-example.json)
- [Example](examples/strata-cloud-manager-api-job-example.json)
- [Example](examples/strata-cloud-manager-api-nat-rule-example.json)
- [Example](examples/strata-cloud-manager-api-nat-rule-list-example.json)
- [Example](examples/strata-cloud-manager-api-nat-rule-request-example.json)
- [Example](examples/strata-cloud-manager-api-security-rule-example.json)
- [Example](examples/strata-cloud-manager-api-security-rule-list-example.json)
- [Example](examples/strata-cloud-manager-api-security-rule-request-example.json)
- [Example](examples/strata-cloud-manager-api-service-example.json)
- [Example](examples/strata-cloud-manager-api-service-list-example.json)
- [Example](examples/strata-cloud-manager-api-service-request-example.json)

### Cloud NGFW API

REST APIs for managing Palo Alto Networks Cloud NGFW, a cloud-native managed firewall service available on AWS and Azure. The API supports creating and managing firewall resources, configuring security rules and rule stacks, managing FQDN lists and prefix lists, and retrieving firewall logs. On AWS, authentication uses IAM roles; on Azure, authentication uses Azure Active Directory.

- **Human URL:** [https://pan.dev/cloudngfw/aws/api/](https://pan.dev/cloudngfw/aws/api/)
- **Base URL:** `https://api.{region}.aws.cloudngfw.paloaltonetworks.com`

#### Tags

- AWS
- Azure
- Cloud Security
- Cloud-Native Firewall
- Managed Service

#### Properties

- [Documentation](https://pan.dev/cloudngfw/aws/api/)
- [Getting Started](https://pan.dev/cloudngfw/docs/getstarted_azure/)
- [OpenAPI](openapi/palo-alto-cloud-ngfw-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/cloud-ngfw-api-firewall-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-firewall-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-firewall-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-fqdn-list-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-fqdn-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-fqdn-list-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-prefix-list-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-prefix-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-prefix-list-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-response-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-rule-destination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-rule-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-rule-stack-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-rule-stack-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-rule-stack-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-security-rule-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-security-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-ngfw-api-security-rule-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/cloud-ngfw-api-firewall-request-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-firewall-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-firewall-summary-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-fqdn-list-request-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-fqdn-list-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-fqdn-list-summary-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-prefix-list-request-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-prefix-list-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-prefix-list-summary-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-response-status-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-rule-destination-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-rule-source-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-rule-stack-request-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-rule-stack-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-rule-stack-summary-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-security-rule-request-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-security-rule-structure.json)
- [JSON Structure](json-structure/cloud-ngfw-api-security-rule-summary-structure.json)
- [JSON-LD](json-ld/palo-alto-cloud-ngfw-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/cloud-ngfw-api-firewall-example.json)
- [Example](examples/cloud-ngfw-api-firewall-request-example.json)
- [Example](examples/cloud-ngfw-api-firewall-summary-example.json)
- [Example](examples/cloud-ngfw-api-fqdn-list-example.json)
- [Example](examples/cloud-ngfw-api-fqdn-list-request-example.json)
- [Example](examples/cloud-ngfw-api-fqdn-list-summary-example.json)
- [Example](examples/cloud-ngfw-api-prefix-list-example.json)
- [Example](examples/cloud-ngfw-api-prefix-list-request-example.json)
- [Example](examples/cloud-ngfw-api-prefix-list-summary-example.json)
- [Example](examples/cloud-ngfw-api-response-status-example.json)
- [Example](examples/cloud-ngfw-api-rule-destination-example.json)
- [Example](examples/cloud-ngfw-api-rule-source-example.json)
- [Example](examples/cloud-ngfw-api-rule-stack-example.json)
- [Example](examples/cloud-ngfw-api-rule-stack-request-example.json)
- [Example](examples/cloud-ngfw-api-rule-stack-summary-example.json)
- [Example](examples/cloud-ngfw-api-security-rule-example.json)
- [Example](examples/cloud-ngfw-api-security-rule-request-example.json)
- [Example](examples/cloud-ngfw-api-security-rule-summary-example.json)

### WildFire API

A cloud-based API for submitting files, URLs, and links for advanced malware analysis in the WildFire sandbox environment. The API returns threat verdicts (benign, malware, grayware, phishing) and detailed analysis reports including behavioral indicators, network activity, and file artifacts. Supports file submission via multipart form upload, verdict queries by hash (MD5, SHA-256), and retrieval of PCAP files and detailed analysis reports.

- **Human URL:** [https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api)
- **Base URL:** `https://wildfire.paloaltonetworks.com/publicapi/`

#### Tags

- File Analysis
- Malware Analysis
- Sandbox
- Threat Prevention
- Verdicts

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api)
- [Getting Started](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api/get-started-with-the-wildfire-api)
- [API Reference](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api)
- [OpenAPI](openapi/palo-alto-wildfire-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/wildfire-api-analysis-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wildfire-api-bulk-verdict-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wildfire-api-sandbox-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wildfire-api-submit-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wildfire-api-verdict-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/wildfire-api-analysis-report-structure.json)
- [JSON Structure](json-structure/wildfire-api-bulk-verdict-response-structure.json)
- [JSON Structure](json-structure/wildfire-api-sandbox-report-structure.json)
- [JSON Structure](json-structure/wildfire-api-submit-response-structure.json)
- [JSON Structure](json-structure/wildfire-api-verdict-response-structure.json)
- [JSON-LD](json-ld/palo-alto-wildfire-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/wildfire-api-analysis-report-example.json)
- [Example](examples/wildfire-api-bulk-verdict-response-example.json)
- [Example](examples/wildfire-api-sandbox-report-example.json)
- [Example](examples/wildfire-api-submit-response-example.json)
- [Example](examples/wildfire-api-verdict-response-example.json)

### Threat Vault API

A REST API for querying Palo Alto Networks threat signature metadata, content release notes, and threat intelligence data. The API provides access to antivirus signatures, anti-spyware signatures, vulnerability protection (IPS) signatures, and file type identification data. Supports queries by signature ID, CVE, threat name, and content release version. Replaces the deprecated AutoFocus API for threat intelligence lookups. Requires an Advanced Threat Prevention or Threat Prevention subscription.

- **Human URL:** [https://pan.dev/threat-vault/api/](https://pan.dev/threat-vault/api/)
- **Base URL:** `https://api.threatvault.paloaltonetworks.com`

#### Tags

- Antivirus
- CVE
- IPS
- Signatures
- Threat Intelligence

#### Properties

- [Documentation](https://pan.dev/threat-vault/api/)
- [Getting Started](https://pan.dev/cdss/docs/getstarted/)
- [Authentication](https://pan.dev/cdss/docs/authentication/)
- [Getting Started](https://pan.dev/cdss/docs/api-call/)
- [OpenAPI](openapi/palo-alto-threat-vault-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/threat-vault-api-api-stats-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/threat-vault-api-atp-report-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/threat-vault-api-atp-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/threat-vault-api-release-note-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/threat-vault-api-release-notes-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/threat-vault-api-threat-history-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/threat-vault-api-threat-history-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/threat-vault-api-threat-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/threat-vault-api-threat-signature-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/threat-vault-api-api-stats-structure.json)
- [JSON Structure](json-structure/threat-vault-api-atp-report-list-structure.json)
- [JSON Structure](json-structure/threat-vault-api-atp-report-structure.json)
- [JSON Structure](json-structure/threat-vault-api-release-note-structure.json)
- [JSON Structure](json-structure/threat-vault-api-release-notes-list-structure.json)
- [JSON Structure](json-structure/threat-vault-api-threat-history-entry-structure.json)
- [JSON Structure](json-structure/threat-vault-api-threat-history-list-structure.json)
- [JSON Structure](json-structure/threat-vault-api-threat-list-structure.json)
- [JSON Structure](json-structure/threat-vault-api-threat-signature-structure.json)
- [JSON-LD](json-ld/palo-alto-threat-vault-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/threat-vault-api-api-stats-example.json)
- [Example](examples/threat-vault-api-atp-report-example.json)
- [Example](examples/threat-vault-api-atp-report-list-example.json)
- [Example](examples/threat-vault-api-release-note-example.json)
- [Example](examples/threat-vault-api-release-notes-list-example.json)
- [Example](examples/threat-vault-api-threat-history-entry-example.json)
- [Example](examples/threat-vault-api-threat-history-list-example.json)
- [Example](examples/threat-vault-api-threat-list-example.json)
- [Example](examples/threat-vault-api-threat-signature-example.json)

### AutoFocus API (Deprecated)

A threat intelligence API that provided contextual information about malware, campaigns, and threat actors observed across the Palo Alto Networks global threat intelligence network. AutoFocus reached end-of-sale on September 30, 2022, and end-of-support on September 30, 2025. Developers should migrate to the Threat Vault API for threat signature lookups and to Cortex XDR or XSIAM for advanced threat intelligence and investigation capabilities.

- **Human URL:** [https://docs.paloaltonetworks.com/autofocus/autofocus-api](https://docs.paloaltonetworks.com/autofocus/autofocus-api)
- **Base URL:** `https://autofocus.paloaltonetworks.com/api/v1.0/`

#### Tags

- Analysis
- Deprecated
- Malware
- Threat Intelligence

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/autofocus/autofocus-api)
- [Getting Started](https://docs.paloaltonetworks.com/autofocus/autofocus-api/get-started-with-the-autofocus-api)
- [Postman Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IoT Security API

A REST API for managing IoT and OT device security including device discovery, profiling, vulnerability assessment, and security policy recommendations. The API provides endpoints for retrieving discovered device inventories, security alerts, vulnerability details, and recommended network segmentation policies. Authentication uses X-Key-Id and X-Access-Key headers with keys generated from the IoT Security portal. Rate limited to 60 requests per minute.

- **Human URL:** [https://pan.dev/iot/api/](https://pan.dev/iot/api/)
- **Base URL:** `https://{customer}.iot.paloaltonetworks.com/pub/v4.0/`

#### Tags

- Asset Discovery
- Device Security
- IoT
- Network Segmentation
- OT Security

#### Properties

- [Documentation](https://pan.dev/iot/api/)
- [OpenAPI](openapi/palo-alto-iot-security-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/iot-security-api-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/iot-security-api-asset-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/iot-security-api-device-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/iot-security-api-device-tag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/iot-security-api-policy-recommendation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/iot-security-api-vulnerability-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/iot-security-api-alert-structure.json)
- [JSON Structure](json-structure/iot-security-api-asset-report-structure.json)
- [JSON Structure](json-structure/iot-security-api-device-structure.json)
- [JSON Structure](json-structure/iot-security-api-device-tag-structure.json)
- [JSON Structure](json-structure/iot-security-api-policy-recommendation-structure.json)
- [JSON Structure](json-structure/iot-security-api-vulnerability-structure.json)
- [JSON-LD](json-ld/palo-alto-iot-security-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/iot-security-api-alert-example.json)
- [Example](examples/iot-security-api-asset-report-example.json)
- [Example](examples/iot-security-api-device-example.json)
- [Example](examples/iot-security-api-device-tag-example.json)
- [Example](examples/iot-security-api-policy-recommendation-example.json)
- [Example](examples/iot-security-api-vulnerability-example.json)

### Data Loss Prevention API

A REST API for managing enterprise data loss prevention across Palo Alto Networks platforms. The API provides access to DLP incidents, policy violation reports, data pattern matches, and remediation workflows. Supports reviewing and managing incidents detected across network traffic, cloud applications, and email channels. Uses SASE OAuth 2.0 authentication aligned with the broader Prisma SASE authentication framework.

- **Human URL:** [https://pan.dev/dlp/api/](https://pan.dev/dlp/api/)
- **Base URL:** `https://api.example.com`

#### Tags

- Compliance
- Data Classification
- Data Security
- DLP
- Incident Management

#### Properties

- [Documentation](https://pan.dev/dlp/api/)
- [OpenAPI](openapi/palo-alto-dlp-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/dlp-api-content-snippet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dlp-api-data-pattern-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dlp-api-dlp-incident-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dlp-api-incident-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/dlp-api-content-snippet-structure.json)
- [JSON Structure](json-structure/dlp-api-data-pattern-structure.json)
- [JSON Structure](json-structure/dlp-api-dlp-incident-structure.json)
- [JSON Structure](json-structure/dlp-api-incident-summary-structure.json)
- [JSON-LD](json-ld/palo-alto-dlp-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/dlp-api-content-snippet-example.json)
- [Example](examples/dlp-api-data-pattern-example.json)
- [Example](examples/dlp-api-dlp-incident-example.json)
- [Example](examples/dlp-api-incident-summary-example.json)

### Prisma Access API

REST APIs for configuring and monitoring Prisma Access, Palo Alto Networks' cloud-delivered SASE platform. The Configuration API manages security policies, remote networks, service connections, and mobile user configurations for cloud-managed tenants. The Insights API (versions 1.0 through 3.0) provides health monitoring, tunnel status, bandwidth utilization, and user connectivity data.

- **Human URL:** [https://pan.dev/access/api/prisma-access-config/](https://pan.dev/access/api/prisma-access-config/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Cloud Security
- Configuration
- Remote Access
- SASE
- Zero Trust

#### Properties

- [Documentation](https://pan.dev/access/api/prisma-access-config/)
- [API Reference](https://pan.dev/access/api/insights/)
- [Getting Started](https://pan.dev/sase/docs/)
- [Changelog](https://pan.dev/sase/docs/release-notes/changelog/)
- [OpenAPI](openapi/palo-alto-prisma-access-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/prisma-access-api-ike-gateway-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-api-ip-sec-tunnel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-api-job-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-api-mobile-agent-infrastructure-settings-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-api-remote-network-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-api-security-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-api-service-connection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-access-api-ike-gateway-structure.json)
- [JSON Structure](json-structure/prisma-access-api-ip-sec-tunnel-structure.json)
- [JSON Structure](json-structure/prisma-access-api-job-status-structure.json)
- [JSON Structure](json-structure/prisma-access-api-mobile-agent-infrastructure-settings-structure.json)
- [JSON Structure](json-structure/prisma-access-api-remote-network-structure.json)
- [JSON Structure](json-structure/prisma-access-api-security-rule-structure.json)
- [JSON Structure](json-structure/prisma-access-api-service-connection-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-access-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-access-api-ike-gateway-example.json)
- [Example](examples/prisma-access-api-ip-sec-tunnel-example.json)
- [Example](examples/prisma-access-api-job-status-example.json)
- [Example](examples/prisma-access-api-mobile-agent-infrastructure-settings-example.json)
- [Example](examples/prisma-access-api-remote-network-example.json)
- [Example](examples/prisma-access-api-security-rule-example.json)
- [Example](examples/prisma-access-api-service-connection-example.json)

### Autonomous DEM API

A REST API for monitoring digital experience metrics within Prisma Access environments. The Autonomous Digital Experience Management (ADEM) API provides application performance data, network path analysis, endpoint health metrics, and user experience scoring. Supports querying performance data by user, application, location, and time range to identify connectivity and performance issues affecting remote and branch users connected through Prisma Access.

- **Human URL:** [https://pan.dev/access/api/adem/autonomous-dem-api/](https://pan.dev/access/api/adem/autonomous-dem-api/)
- **Base URL:** `https://api.example.com`

#### Tags

- Digital Experience
- Monitoring
- Network Analytics
- Performance
- SASE

#### Properties

- [Documentation](https://pan.dev/access/api/adem/autonomous-dem-api/)
- [Getting Started](https://pan.dev/access/docs/adem/getstarted/)
- [OpenAPI](openapi/palo-alto-autonomous-dem-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/autonomous-dem-api-agent-score-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/autonomous-dem-api-application-score-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/autonomous-dem-api-monitored-agent-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/autonomous-dem-api-monitored-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/autonomous-dem-api-performance-metric-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/autonomous-dem-api-test-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/autonomous-dem-api-agent-score-structure.json)
- [JSON Structure](json-structure/autonomous-dem-api-application-score-structure.json)
- [JSON Structure](json-structure/autonomous-dem-api-monitored-agent-structure.json)
- [JSON Structure](json-structure/autonomous-dem-api-monitored-application-structure.json)
- [JSON Structure](json-structure/autonomous-dem-api-performance-metric-structure.json)
- [JSON Structure](json-structure/autonomous-dem-api-test-result-structure.json)
- [JSON-LD](json-ld/palo-alto-autonomous-dem-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/autonomous-dem-api-agent-score-example.json)
- [Example](examples/autonomous-dem-api-application-score-example.json)
- [Example](examples/autonomous-dem-api-monitored-agent-example.json)
- [Example](examples/autonomous-dem-api-monitored-application-example.json)
- [Example](examples/autonomous-dem-api-performance-metric-example.json)
- [Example](examples/autonomous-dem-api-test-result-example.json)

### Prisma SD-WAN API

REST APIs for managing Prisma SD-WAN (formerly CloudGenix) branch networking infrastructure. The API supports configuration of sites, WAN interfaces, routing policies, application definitions, path quality monitoring, and network analytics. Provides both a unified API using SASE OAuth 2.0 authentication and a legacy API with session token authentication.

- **Human URL:** [https://pan.dev/sdwan/docs/](https://pan.dev/sdwan/docs/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Branch Networking
- CloudGenix
- Routing
- SD-WAN
- WAN Optimization

#### Properties

- [Documentation](https://pan.dev/sdwan/docs/)
- [API Reference](https://pan.dev/sdwan/api/)
- [OpenAPI](openapi/palo-alto-prisma-sd-wan-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/prisma-sd-wan-api-alarm-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-sd-wan-api-application-usage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-sd-wan-api-lan-network-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-sd-wan-api-path-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-sd-wan-api-qo-s-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-sd-wan-api-site-metric-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-sd-wan-api-site-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-sd-wan-api-wan-interface-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-sd-wan-api-alarm-structure.json)
- [JSON Structure](json-structure/prisma-sd-wan-api-application-usage-structure.json)
- [JSON Structure](json-structure/prisma-sd-wan-api-lan-network-structure.json)
- [JSON Structure](json-structure/prisma-sd-wan-api-path-rule-structure.json)
- [JSON Structure](json-structure/prisma-sd-wan-api-qo-s-rule-structure.json)
- [JSON Structure](json-structure/prisma-sd-wan-api-site-metric-structure.json)
- [JSON Structure](json-structure/prisma-sd-wan-api-site-structure.json)
- [JSON Structure](json-structure/prisma-sd-wan-api-wan-interface-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-sd-wan-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-sd-wan-api-alarm-example.json)
- [Example](examples/prisma-sd-wan-api-application-usage-example.json)
- [Example](examples/prisma-sd-wan-api-lan-network-example.json)
- [Example](examples/prisma-sd-wan-api-path-rule-example.json)
- [Example](examples/prisma-sd-wan-api-qo-s-rule-example.json)
- [Example](examples/prisma-sd-wan-api-site-example.json)
- [Example](examples/prisma-sd-wan-api-site-metric-example.json)
- [Example](examples/prisma-sd-wan-api-wan-interface-example.json)

### Prisma Cloud CSPM API

The Cloud Security Posture Management API for Prisma Cloud (formerly RedLock) providing programmatic access to cloud security monitoring across AWS, Azure, GCP, and Oracle Cloud. The API supports managing security alerts, compliance policies, cloud accounts, asset inventories, and remediation workflows. Endpoints cover alert management, policy configuration, compliance reporting, cloud account onboarding, resource queries using RQL (Resource Query Language), and integration management.

- **Human URL:** [https://pan.dev/prisma-cloud/api/cspm/](https://pan.dev/prisma-cloud/api/cspm/)
- **Base URL:** `https://api.prismacloud.io`

#### Tags

- Cloud Posture
- Cloud Security
- Compliance
- CSPM
- Multi-Cloud

#### Properties

- [Documentation](https://pan.dev/prisma-cloud/api/cspm/)
- [Authentication](https://prisma.pan.dev/api/cloud/api-auth/)
- [Getting Started](https://pan.dev/prisma-cloud/docs/cspm/cspm-gs/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-cspm-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/palo-alto-prisma-cloud-webhooks-asyncapi-original.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/prisma-cloud-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-cspm-api-alert-filter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-cspm-api-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-cspm-api-cloud-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-cspm-api-compliance-standard-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-cspm-api-policy-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-cspm-api-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-cspm-api-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-cspm-api-search-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-cspm-api-time-range-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-webhooks-alert-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-cloud-cspm-api-alert-filter-structure.json)
- [JSON Structure](json-structure/prisma-cloud-cspm-api-alert-structure.json)
- [JSON Structure](json-structure/prisma-cloud-cspm-api-cloud-account-structure.json)
- [JSON Structure](json-structure/prisma-cloud-cspm-api-compliance-standard-structure.json)
- [JSON Structure](json-structure/prisma-cloud-cspm-api-policy-input-structure.json)
- [JSON Structure](json-structure/prisma-cloud-cspm-api-policy-structure.json)
- [JSON Structure](json-structure/prisma-cloud-cspm-api-report-structure.json)
- [JSON Structure](json-structure/prisma-cloud-cspm-api-search-result-structure.json)
- [JSON Structure](json-structure/prisma-cloud-cspm-api-time-range-structure.json)
- [JSON Structure](json-structure/prisma-cloud-policy-structure.json)
- [JSON Structure](json-structure/prisma-cloud-webhooks-alert-payload-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-cloud-cspm-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/palo-alto-prisma-cloud-webhooks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-cloud-cspm-api-alert-example.json)
- [Example](examples/prisma-cloud-cspm-api-alert-filter-example.json)
- [Example](examples/prisma-cloud-cspm-api-cloud-account-example.json)
- [Example](examples/prisma-cloud-cspm-api-compliance-standard-example.json)
- [Example](examples/prisma-cloud-cspm-api-policy-example.json)
- [Example](examples/prisma-cloud-cspm-api-policy-input-example.json)
- [Example](examples/prisma-cloud-cspm-api-report-example.json)
- [Example](examples/prisma-cloud-cspm-api-search-result-example.json)
- [Example](examples/prisma-cloud-cspm-api-time-range-example.json)
- [Example](examples/prisma-cloud-policy-example.json)
- [Example](examples/prisma-cloud-webhooks-alert-payload-example.json)
- [JSON-LD](json-ld/palo-alto-prisma-cloud-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Prisma Cloud Compute API

The Cloud Workload Protection Platform (CWPP) API for Prisma Cloud (formerly Twistlock) providing security for containers, hosts, and serverless functions. The API covers image vulnerability scanning, runtime defense policies, compliance checks, registry scanning, CI/CD pipeline integration, and defender deployment management. Supports both SaaS and self-hosted Console deployments.

- **Human URL:** [https://pan.dev/compute/api/](https://pan.dev/compute/api/)
- **Base URL:** `https://{console}/api/v1`

#### Tags

- Container Security
- CWPP
- Kubernetes
- Runtime Protection
- Serverless

#### Properties

- [Documentation](https://pan.dev/compute/api/)
- [Authentication](https://pan.dev/compute/api/access-api-self-hosted/)
- [API Reference](https://pan.dev/compute/api/stable-endpoints/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-compute-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/prisma-cloud-compute-api-ci-scan-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-compliance-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-compliance-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-container-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-defender-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-defender-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-host-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-image-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-registry-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-runtime-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-vulnerability-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-compute-api-vulnerability-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-cloud-compute-api-ci-scan-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-compliance-issue-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-compliance-policy-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-container-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-defender-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-defender-summary-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-host-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-image-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-registry-config-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-runtime-policy-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-vulnerability-policy-structure.json)
- [JSON Structure](json-structure/prisma-cloud-compute-api-vulnerability-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-cloud-compute-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-cloud-compute-api-ci-scan-example.json)
- [Example](examples/prisma-cloud-compute-api-compliance-issue-example.json)
- [Example](examples/prisma-cloud-compute-api-compliance-policy-example.json)
- [Example](examples/prisma-cloud-compute-api-container-example.json)
- [Example](examples/prisma-cloud-compute-api-defender-example.json)
- [Example](examples/prisma-cloud-compute-api-defender-summary-example.json)
- [Example](examples/prisma-cloud-compute-api-host-example.json)
- [Example](examples/prisma-cloud-compute-api-image-example.json)
- [Example](examples/prisma-cloud-compute-api-registry-config-example.json)
- [Example](examples/prisma-cloud-compute-api-runtime-policy-example.json)
- [Example](examples/prisma-cloud-compute-api-vulnerability-example.json)
- [Example](examples/prisma-cloud-compute-api-vulnerability-policy-example.json)

### Prisma Cloud Code Security API

A REST API for Prisma Cloud Application Security (formerly Bridgecrew) providing infrastructure-as-code scanning, software composition analysis, and supply chain security. The API supports checking Terraform, CloudFormation, Kubernetes manifests, and Dockerfiles against security policies, managing code repositories, retrieving scan results, and configuring fix suggestions. Integrates with CI/CD pipelines for shift-left security enforcement during the development lifecycle.

- **Human URL:** [https://pan.dev/prisma-cloud/api/code/](https://pan.dev/prisma-cloud/api/code/)
- **Base URL:** `https://api.prismacloud.io`

#### Tags

- Code Security
- DevSecOps
- IaC Scanning
- Shift Left
- Supply Chain

#### Properties

- [Documentation](https://pan.dev/prisma-cloud/api/code/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-code-security-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/prisma-cloud-code-security-api-code-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-code-security-api-fix-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-code-security-api-repository-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-code-security-api-scan-integration-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-code-security-api-scan-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-code-security-api-suppression-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-cloud-code-security-api-code-error-structure.json)
- [JSON Structure](json-structure/prisma-cloud-code-security-api-fix-structure.json)
- [JSON Structure](json-structure/prisma-cloud-code-security-api-repository-structure.json)
- [JSON Structure](json-structure/prisma-cloud-code-security-api-scan-integration-structure.json)
- [JSON Structure](json-structure/prisma-cloud-code-security-api-scan-status-structure.json)
- [JSON Structure](json-structure/prisma-cloud-code-security-api-suppression-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-cloud-code-security-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-cloud-code-security-api-code-error-example.json)
- [Example](examples/prisma-cloud-code-security-api-fix-example.json)
- [Example](examples/prisma-cloud-code-security-api-repository-example.json)
- [Example](examples/prisma-cloud-code-security-api-scan-integration-example.json)
- [Example](examples/prisma-cloud-code-security-api-scan-status-example.json)
- [Example](examples/prisma-cloud-code-security-api-suppression-example.json)

### Cortex XDR API

A REST API for the Cortex XDR extended detection and response platform providing programmatic access to incident management, alert handling, endpoint operations, and threat hunting. Key API modules include incidents (get, update, close), alerts (get details, exclusions), endpoints (isolate, unisolate, scan, get agent info), scripts (execute, get results), and audit logs.

- **Human URL:** [https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API)
- **Base URL:** `https://api-{fqdn}/public_api/v1/`

#### Tags

- Detection
- Endpoint Security
- Incidents
- Response
- XDR

#### Properties

- [Documentation](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API)
- [Getting Started](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API/Get-Started-with-APIs)
- [API Reference](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API/API-Reference)
- [OpenAPI](openapi/palo-alto-cortex-xdr-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/palo-alto-cortex-xdr-webhooks-asyncapi-original.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/cortex-xdr-incident-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xdr-api-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xdr-api-audit-log-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xdr-api-endpoint-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xdr-api-filter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xdr-api-incident-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xdr-api-incident-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xdr-api-sort-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xdr-webhooks-alert-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xdr-webhooks-incident-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/cortex-xdr-api-alert-structure.json)
- [JSON Structure](json-structure/cortex-xdr-api-audit-log-structure.json)
- [JSON Structure](json-structure/cortex-xdr-api-endpoint-structure.json)
- [JSON Structure](json-structure/cortex-xdr-api-filter-structure.json)
- [JSON Structure](json-structure/cortex-xdr-api-incident-detail-structure.json)
- [JSON Structure](json-structure/cortex-xdr-api-incident-structure.json)
- [JSON Structure](json-structure/cortex-xdr-api-sort-order-structure.json)
- [JSON Structure](json-structure/cortex-xdr-incident-structure.json)
- [JSON Structure](json-structure/cortex-xdr-webhooks-alert-payload-structure.json)
- [JSON Structure](json-structure/cortex-xdr-webhooks-incident-payload-structure.json)
- [JSON-LD](json-ld/palo-alto-cortex-xdr-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/palo-alto-cortex-xdr-webhooks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/cortex-xdr-api-alert-example.json)
- [Example](examples/cortex-xdr-api-audit-log-example.json)
- [Example](examples/cortex-xdr-api-endpoint-example.json)
- [Example](examples/cortex-xdr-api-filter-example.json)
- [Example](examples/cortex-xdr-api-incident-detail-example.json)
- [Example](examples/cortex-xdr-api-incident-example.json)
- [Example](examples/cortex-xdr-api-sort-order-example.json)
- [Example](examples/cortex-xdr-incident-example.json)
- [Example](examples/cortex-xdr-webhooks-alert-payload-example.json)
- [Example](examples/cortex-xdr-webhooks-incident-payload-example.json)
- [JSON-LD](json-ld/palo-alto-cortex-xdr-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Cortex XSOAR API

APIs and development framework for Cortex XSOAR (formerly Demisto), the security orchestration, automation, and response platform. The REST API provides programmatic access to incidents, investigations, war rooms, playbooks, and integration instances. The integration development framework enables building custom integrations for the XSOAR marketplace with 750+ verified integrations. Supports Python and PowerShell integration development with the demisto-sdk CLI tool.

- **Human URL:** [https://xsoar.pan.dev/](https://xsoar.pan.dev/)
- **Base URL:** `https://{xsoar-server}/`

#### Tags

- Automation
- Incident Response
- Integrations
- Playbooks
- SOAR

#### Properties

- [Documentation](https://xsoar.pan.dev/)
- [API Reference](https://xsoar.pan.dev/docs/reference/api/demisto-class)
- [Getting Started](https://xsoar.pan.dev/docs/concepts/getting-started-guide)
- [API Reference](https://xsoar.pan.dev/docs/reference/index)
- [Marketplace](https://cortex.marketplace.pan.dev/marketplace/)
- [GitHub Repository](https://github.com/demisto/content)
- [JSON Schema](json-schema/cortex-xsoar-integration-manifest-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [OpenAPI](openapi/palo-alto-cortex-xsoar-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/cortex-xsoar-api-create-entry-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsoar-api-create-incident-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsoar-api-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsoar-api-incident-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsoar-api-incident-search-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsoar-api-incident-search-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsoar-api-integration-instance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsoar-api-integration-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsoar-api-investigation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsoar-api-playbook-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsoar-api-update-incident-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/cortex-xsoar-api-create-entry-request-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-api-create-incident-request-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-api-entry-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-api-incident-search-request-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-api-incident-search-response-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-api-incident-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-api-integration-instance-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-api-integration-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-api-investigation-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-api-playbook-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-api-update-incident-request-structure.json)
- [JSON Structure](json-structure/cortex-xsoar-integration-manifest-structure.json)
- [JSON-LD](json-ld/palo-alto-cortex-xsoar-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/cortex-xsoar-api-create-entry-request-example.json)
- [Example](examples/cortex-xsoar-api-create-incident-request-example.json)
- [Example](examples/cortex-xsoar-api-entry-example.json)
- [Example](examples/cortex-xsoar-api-incident-example.json)
- [Example](examples/cortex-xsoar-api-incident-search-request-example.json)
- [Example](examples/cortex-xsoar-api-incident-search-response-example.json)
- [Example](examples/cortex-xsoar-api-integration-example.json)
- [Example](examples/cortex-xsoar-api-integration-instance-example.json)
- [Example](examples/cortex-xsoar-api-investigation-example.json)
- [Example](examples/cortex-xsoar-api-playbook-example.json)
- [Example](examples/cortex-xsoar-api-update-incident-request-example.json)
- [Example](examples/cortex-xsoar-integration-manifest-example.json)
- [JSON-LD](json-ld/palo-alto-cortex-xsoar-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Cortex XSIAM API

A REST API for Cortex XSIAM, the AI-driven security operations platform that combines SIEM, XDR, SOAR, and ASM capabilities. The API provides endpoints for incident management, alert handling, data ingestion configuration, XQL query execution, asset management, and automation rule management. Shares endpoint patterns with Cortex XDR but includes additional capabilities for log collection configuration, data model management, and AI-assisted investigation.

- **Human URL:** [https://docs-cortex.paloaltonetworks.com/r/Cortex-XSIAM-REST-API](https://docs-cortex.paloaltonetworks.com/r/Cortex-XSIAM-REST-API)
- **Base URL:** `https://api-{fqdn}/public_api/v1/`

#### Tags

- AI-Driven SOC
- Automation
- Security Analytics
- SIEM
- XDR

#### Properties

- [Documentation](https://docs-cortex.paloaltonetworks.com/r/Cortex-XSIAM-REST-API)
- [Getting Started](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API/Get-Started-with-APIs)
- [OpenAPI](openapi/palo-alto-cortex-xsiam-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/palo-alto-cortex-xsiam-data-ingestion-asyncapi-original.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/cortex-xsiam-api-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsiam-api-asset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsiam-api-audit-log-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsiam-api-endpoint-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsiam-api-filter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsiam-api-incident-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsiam-api-sort-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsiam-data-ingestion-event-data-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsiam-data-ingestion-log-data-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xsiam-data-ingestion-xdr-data-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/cortex-xsiam-api-alert-structure.json)
- [JSON Structure](json-structure/cortex-xsiam-api-asset-structure.json)
- [JSON Structure](json-structure/cortex-xsiam-api-audit-log-structure.json)
- [JSON Structure](json-structure/cortex-xsiam-api-endpoint-structure.json)
- [JSON Structure](json-structure/cortex-xsiam-api-filter-structure.json)
- [JSON Structure](json-structure/cortex-xsiam-api-incident-structure.json)
- [JSON Structure](json-structure/cortex-xsiam-api-sort-order-structure.json)
- [JSON Structure](json-structure/cortex-xsiam-data-ingestion-event-data-payload-structure.json)
- [JSON Structure](json-structure/cortex-xsiam-data-ingestion-log-data-payload-structure.json)
- [JSON Structure](json-structure/cortex-xsiam-data-ingestion-xdr-data-payload-structure.json)
- [JSON-LD](json-ld/palo-alto-cortex-xsiam-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/palo-alto-cortex-xsiam-data-ingestion-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/cortex-xsiam-api-alert-example.json)
- [Example](examples/cortex-xsiam-api-asset-example.json)
- [Example](examples/cortex-xsiam-api-audit-log-example.json)
- [Example](examples/cortex-xsiam-api-endpoint-example.json)
- [Example](examples/cortex-xsiam-api-filter-example.json)
- [Example](examples/cortex-xsiam-api-incident-example.json)
- [Example](examples/cortex-xsiam-api-sort-order-example.json)
- [Example](examples/cortex-xsiam-data-ingestion-event-data-payload-example.json)
- [Example](examples/cortex-xsiam-data-ingestion-log-data-payload-example.json)
- [Example](examples/cortex-xsiam-data-ingestion-xdr-data-payload-example.json)

### Prisma AIRS AI Runtime Security API

The AI Runtime Security API (API Intercept) for securing generative AI applications, AI models, AI data, and AI agents against prompt injection, data leakage, toxic content, malicious URLs, database security attacks, malicious code, and other AI-specific threats. Provides Scan APIs for real-time threat detection on prompts and model responses, and Management APIs for configuring security profiles, API keys, and deployments. Supports Secure MCP, custom topic guardrails, contextual grounding, and data masking. Available in US, EU (Germany), India, and Singapore regions. Integrates via REST API or the pan-aisecurity Python SDK with API key or OAuth 2.0 authentication.

- **Human URL:** [https://pan.dev/airs/](https://pan.dev/airs/)
- **Base URL:** `https://service.api.aisecurity.paloaltonetworks.com`

#### Tags

- AI Runtime
- AI Security
- API Intercept
- GenAI
- LLM Security
- MCP Security
- Prompt Injection

#### Properties

- [Documentation](https://pan.dev/airs/)
- [API Reference](https://pan.dev/prisma-airs/api/airuntimesecurity/airuntimesecurityapi/)
- [Getting Started](https://docs.paloaltonetworks.com/ai-runtime-security/activation-and-onboarding/ai-runtime-security-api-intercept-overview)
- [SDK](https://pan.dev/prisma-airs/api/airuntimesecurity/pythonsdk/)
- [GitHub Repository](https://github.com/PaloAltoNetworks/aisecurity-python-sdk)
- [SDK](https://github.com/PaloAltoNetworks/airs-api-mgmt-sdk)
- [OpenAPI](openapi/palo-alto-prisma-airs-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/prisma-airs-api-ai-profile-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-airs-api-content-scan-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-airs-api-scan-content-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-airs-api-scan-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-airs-api-scan-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-airs-api-ai-profile-structure.json)
- [JSON Structure](json-structure/prisma-airs-api-content-scan-result-structure.json)
- [JSON Structure](json-structure/prisma-airs-api-scan-content-structure.json)
- [JSON Structure](json-structure/prisma-airs-api-scan-request-structure.json)
- [JSON Structure](json-structure/prisma-airs-api-scan-response-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-airs-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-airs-api-ai-profile-example.json)
- [Example](examples/prisma-airs-api-content-scan-result-example.json)
- [Example](examples/prisma-airs-api-scan-content-example.json)
- [Example](examples/prisma-airs-api-scan-request-example.json)
- [Example](examples/prisma-airs-api-scan-response-example.json)

### Security Advisory API

A REST API (currently in beta) for programmatically querying Palo Alto Networks security advisories published by the Product Security Incident Response Team (PSIRT). The API supports filtering advisories by CVE ID, severity, product, and date range. Returns advisory details including vulnerability descriptions, affected versions, CVSS scores, and remediation guidance. Also available as an RSS feed for continuous monitoring of new security advisories.

- **Human URL:** [https://security.paloaltonetworks.com/api](https://security.paloaltonetworks.com/api)
- **Base URL:** `https://security.paloaltonetworks.com`

#### Tags

- CVE
- Patching
- PSIRT
- Security Advisories
- Vulnerabilities

#### Properties

- [Documentation](https://security.paloaltonetworks.com/api)
- [Feed](https://security.paloaltonetworks.com/rss.xml)
- [OpenAPI](openapi/palo-alto-security-advisory-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/palo-alto-security-advisory-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/security-advisory-api-advisory-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/security-advisory-api-affected-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/security-advisory-api-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/palo-alto-security-advisory-structure.json)
- [JSON Structure](json-structure/security-advisory-api-advisory-structure.json)
- [JSON Structure](json-structure/security-advisory-api-affected-product-structure.json)
- [JSON Structure](json-structure/security-advisory-api-product-structure.json)
- [JSON-LD](json-ld/palo-alto-security-advisory-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/palo-alto-security-advisory-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/palo-alto-security-advisory-example.json)
- [Example](examples/security-advisory-api-advisory-example.json)
- [Example](examples/security-advisory-api-affected-product-example.json)
- [Example](examples/security-advisory-api-product-example.json)

### Cortex Xpanse API

A REST API for Cortex Xpanse, the attack surface management platform that discovers, evaluates, and mitigates risks on internet-facing assets. The API provides programmatic access to asset inventories, attack surface rules, risk identification, and remediation workflows. Supports querying discovered services, certificates, domains, and cloud resources exposed to the internet. Authentication uses RBAC API key pairs consistent with other Cortex platform APIs.

- **Human URL:** [https://docs-cortex.paloaltonetworks.com/r/Cortex-Xpanse-REST-API](https://docs-cortex.paloaltonetworks.com/r/Cortex-Xpanse-REST-API)
- **Base URL:** `https://api-{fqdn}/public_api/v1/`

#### Tags

- Asset Discovery
- Attack Surface Management
- Exposure Management
- Internet-Facing Assets
- Risk Assessment

#### Properties

- [Documentation](https://docs-cortex.paloaltonetworks.com/r/Cortex-Xpanse-REST-API)
- [OpenAPI](openapi/palo-alto-cortex-xpanse-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/cortex-xpanse-api-asm-incident-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xpanse-api-asset-internet-exposure-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xpanse-api-asset-internet-exposure-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xpanse-api-attack-surface-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xpanse-api-audit-log-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xpanse-api-exposed-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xpanse-api-filter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xpanse-api-owned-ip-range-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cortex-xpanse-api-sort-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/cortex-xpanse-api-asm-incident-structure.json)
- [JSON Structure](json-structure/cortex-xpanse-api-asset-internet-exposure-detail-structure.json)
- [JSON Structure](json-structure/cortex-xpanse-api-asset-internet-exposure-structure.json)
- [JSON Structure](json-structure/cortex-xpanse-api-attack-surface-rule-structure.json)
- [JSON Structure](json-structure/cortex-xpanse-api-audit-log-structure.json)
- [JSON Structure](json-structure/cortex-xpanse-api-exposed-service-structure.json)
- [JSON Structure](json-structure/cortex-xpanse-api-filter-structure.json)
- [JSON Structure](json-structure/cortex-xpanse-api-owned-ip-range-structure.json)
- [JSON Structure](json-structure/cortex-xpanse-api-sort-order-structure.json)
- [JSON-LD](json-ld/palo-alto-cortex-xpanse-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/cortex-xpanse-api-asm-incident-example.json)
- [Example](examples/cortex-xpanse-api-asset-internet-exposure-detail-example.json)
- [Example](examples/cortex-xpanse-api-asset-internet-exposure-example.json)
- [Example](examples/cortex-xpanse-api-attack-surface-rule-example.json)
- [Example](examples/cortex-xpanse-api-audit-log-example.json)
- [Example](examples/cortex-xpanse-api-exposed-service-example.json)
- [Example](examples/cortex-xpanse-api-filter-example.json)
- [Example](examples/cortex-xpanse-api-owned-ip-range-example.json)
- [Example](examples/cortex-xpanse-api-sort-order-example.json)

### DNS Security API

A REST API (currently in beta) for retrieving DNS domain details, categorization information, and contextual network access statistics from the Palo Alto Networks DNS Security service. Supports querying domain reputation, categorization data, and related threat intelligence. Requires a DNS Security subscription and uses API key authentication via the X-DNS-API-APIKEY header.

- **Human URL:** [https://pan.dev/dns-security/api/](https://pan.dev/dns-security/api/)
- **Base URL:** `https://api.dns.service.paloaltonetworks.com`

#### Tags

- Beta
- DNS
- Domain Categorization
- Domain Security
- Threat Intelligence

#### Properties

- [Documentation](https://pan.dev/dns-security/api/)
- [Getting Started](https://pan.dev/cdss/docs/getstarted/)
- [Authentication](https://pan.dev/cdss/docs/authentication/)
- [OpenAPI](openapi/palo-alto-dns-security-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/dns-security-api-domain-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dns-security-api-network-stats-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/dns-security-api-domain-detail-structure.json)
- [JSON Structure](json-structure/dns-security-api-network-stats-structure.json)
- [JSON-LD](json-ld/palo-alto-dns-security-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/dns-security-api-domain-detail-example.json)
- [Example](examples/dns-security-api-network-stats-example.json)

### Email DLP API

A REST API for programmatically reviewing and managing Email DLP incidents detected across enterprise email channels. The API supports retrieving incident details, updating verdicts on flagged emails, and managing remediation workflows for data loss prevention violations in email traffic. Uses region-specific endpoints and requires SOC_Admin, Superuser, or Data Security Administrator roles for access.

- **Human URL:** [https://pan.dev/email-dlp/api/](https://pan.dev/email-dlp/api/)
- **Base URL:** `https://api.example.com`

#### Tags

- Compliance
- Data Protection
- DLP
- Email Security
- Incident Management

#### Properties

- [Documentation](https://pan.dev/email-dlp/api/)
- [OpenAPI](openapi/palo-alto-email-dlp-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/email-dlp-api-email-attachment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/email-dlp-api-email-dlp-incident-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/email-dlp-api-email-recipient-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/email-dlp-api-email-attachment-structure.json)
- [JSON Structure](json-structure/email-dlp-api-email-dlp-incident-structure.json)
- [JSON Structure](json-structure/email-dlp-api-email-recipient-structure.json)
- [JSON-LD](json-ld/palo-alto-email-dlp-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/email-dlp-api-email-attachment-example.json)
- [Example](examples/email-dlp-api-email-dlp-incident-example.json)
- [Example](examples/email-dlp-api-email-recipient-example.json)

### SaaS Security API

A REST API for scanning and protecting assets stored in sanctioned SaaS applications. The API provides at-rest detection, inspection, and remediation capabilities for data stored across cloud applications including file scanning, policy violation detection, and automated remediation workflows. Supports integration with enterprise SaaS applications for continuous data security monitoring.

- **Human URL:** [https://docs.paloaltonetworks.com/saas-security/saas-security-admin/saas-security-api](https://docs.paloaltonetworks.com/saas-security/saas-security-admin/saas-security-api)
- **Base URL:** `https://api.example.com`

#### Tags

- CASB
- Cloud Applications
- Compliance
- Data Protection
- SaaS Security

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/saas-security/saas-security-admin/saas-security-api)
- [OpenAPI](openapi/palo-alto-saas-security-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/saas-security-api-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/saas-security-api-asset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/saas-security-api-incident-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/saas-security-api-log-forwarding-settings-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/saas-security-api-user-activity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/saas-security-api-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/saas-security-api-application-structure.json)
- [JSON Structure](json-structure/saas-security-api-asset-structure.json)
- [JSON Structure](json-structure/saas-security-api-incident-structure.json)
- [JSON Structure](json-structure/saas-security-api-log-forwarding-settings-structure.json)
- [JSON Structure](json-structure/saas-security-api-user-activity-structure.json)
- [JSON Structure](json-structure/saas-security-api-user-structure.json)
- [JSON-LD](json-ld/palo-alto-saas-security-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/saas-security-api-application-example.json)
- [Example](examples/saas-security-api-asset-example.json)
- [Example](examples/saas-security-api-incident-example.json)
- [Example](examples/saas-security-api-log-forwarding-settings-example.json)
- [Example](examples/saas-security-api-user-activity-example.json)
- [Example](examples/saas-security-api-user-example.json)

### SaaS Security Posture Management API

A REST API for managing SaaS Security Posture Management providing continuous monitoring of misconfigured SaaS application settings. The API supports managing onboarded SaaS applications, retrieving configuration assessment details, accessing the application catalog, and managing JIRA integrations for remediation tracking. Part of the broader SASE platform with OAuth 2.0 authentication.

- **Human URL:** [https://pan.dev/sase/api/sspm/](https://pan.dev/sase/api/sspm/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Compliance
- Misconfiguration
- SaaS Applications
- SaaS Posture
- SSPM

#### Properties

- [Documentation](https://pan.dev/sase/api/sspm/)
- [OpenAPI](openapi/palo-alto-sspm-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sspm-api-catalog-app-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sspm-api-jira-integration-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sspm-api-jira-integration-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sspm-api-onboard-app-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sspm-api-onboarded-app-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sspm-api-posture-check-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sspm-api-catalog-app-structure.json)
- [JSON Structure](json-structure/sspm-api-jira-integration-request-structure.json)
- [JSON Structure](json-structure/sspm-api-jira-integration-structure.json)
- [JSON Structure](json-structure/sspm-api-onboard-app-request-structure.json)
- [JSON Structure](json-structure/sspm-api-onboarded-app-structure.json)
- [JSON Structure](json-structure/sspm-api-posture-check-structure.json)
- [JSON-LD](json-ld/palo-alto-sspm-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/sspm-api-catalog-app-example.json)
- [Example](examples/sspm-api-jira-integration-example.json)
- [Example](examples/sspm-api-jira-integration-request-example.json)
- [Example](examples/sspm-api-onboard-app-request-example.json)
- [Example](examples/sspm-api-onboarded-app-example.json)
- [Example](examples/sspm-api-posture-check-example.json)

### ZTNA Connector API

REST APIs for managing Zero Trust Network Access connectors within the Prisma Access SASE platform. The API supports creating and managing ZTNA connectors, applications, licenses, and connector groups for providing secure application access without traditional VPN infrastructure. Uses the common SASE OAuth 2.0 authentication framework with tenant service group credentials.

- **Human URL:** [https://pan.dev/access/api/ztna/ztna-connector-apis/](https://pan.dev/access/api/ztna/ztna-connector-apis/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Connectors
- Network Access
- SASE
- Zero Trust
- ZTNA

#### Properties

- [Documentation](https://pan.dev/access/api/ztna/ztna-connector-apis/)
- [API Reference](https://pan.dev/access/api/ztna/ztna-connector-restful-api/)
- [OpenAPI](openapi/palo-alto-ztna-connector-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/ztna-connector-api-connector-group-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ztna-connector-api-connector-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ztna-connector-api-connector-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ztna-connector-api-connector-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ztna-connector-api-fqdn-rule-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ztna-connector-api-fqdn-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ztna-connector-api-license-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ztna-connector-api-subnet-rule-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ztna-connector-api-subnet-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ztna-connector-api-ztna-application-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ztna-connector-api-ztna-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/ztna-connector-api-connector-group-request-structure.json)
- [JSON Structure](json-structure/ztna-connector-api-connector-group-structure.json)
- [JSON Structure](json-structure/ztna-connector-api-connector-request-structure.json)
- [JSON Structure](json-structure/ztna-connector-api-connector-structure.json)
- [JSON Structure](json-structure/ztna-connector-api-fqdn-rule-request-structure.json)
- [JSON Structure](json-structure/ztna-connector-api-fqdn-rule-structure.json)
- [JSON Structure](json-structure/ztna-connector-api-license-info-structure.json)
- [JSON Structure](json-structure/ztna-connector-api-subnet-rule-request-structure.json)
- [JSON Structure](json-structure/ztna-connector-api-subnet-rule-structure.json)
- [JSON Structure](json-structure/ztna-connector-api-ztna-application-request-structure.json)
- [JSON Structure](json-structure/ztna-connector-api-ztna-application-structure.json)
- [JSON-LD](json-ld/palo-alto-ztna-connector-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/ztna-connector-api-connector-example.json)
- [Example](examples/ztna-connector-api-connector-group-example.json)
- [Example](examples/ztna-connector-api-connector-group-request-example.json)
- [Example](examples/ztna-connector-api-connector-request-example.json)
- [Example](examples/ztna-connector-api-fqdn-rule-example.json)
- [Example](examples/ztna-connector-api-fqdn-rule-request-example.json)
- [Example](examples/ztna-connector-api-license-info-example.json)
- [Example](examples/ztna-connector-api-subnet-rule-example.json)
- [Example](examples/ztna-connector-api-subnet-rule-request-example.json)
- [Example](examples/ztna-connector-api-ztna-application-example.json)
- [Example](examples/ztna-connector-api-ztna-application-request-example.json)

### Prisma Access Browser API

REST APIs for scaling and automating processes related to the Prisma Access secure enterprise browser. The API supports browser deployment management, policy configuration, and user management for the cloud-delivered secure browser solution. Supports Super User (read/write) and View-Only Administrator roles for access control.

- **Human URL:** [https://pan.dev/access/api/browser-mgmt/browser-mgmt-api/](https://pan.dev/access/api/browser-mgmt/browser-mgmt-api/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Browser Management
- Enterprise Browser
- SASE
- Secure Browser
- Web Security

#### Properties

- [Documentation](https://pan.dev/access/api/browser-mgmt/browser-mgmt-api/)
- [OpenAPI](openapi/palo-alto-prisma-access-browser-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/prisma-access-browser-api-browser-deployment-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-browser-api-browser-deployment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-browser-api-browser-policy-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-browser-api-browser-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-browser-api-browser-session-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-browser-api-browser-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-browser-api-managed-device-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-browser-api-usage-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-access-browser-api-browser-deployment-request-structure.json)
- [JSON Structure](json-structure/prisma-access-browser-api-browser-deployment-structure.json)
- [JSON Structure](json-structure/prisma-access-browser-api-browser-policy-request-structure.json)
- [JSON Structure](json-structure/prisma-access-browser-api-browser-policy-structure.json)
- [JSON Structure](json-structure/prisma-access-browser-api-browser-session-structure.json)
- [JSON Structure](json-structure/prisma-access-browser-api-browser-user-structure.json)
- [JSON Structure](json-structure/prisma-access-browser-api-managed-device-structure.json)
- [JSON Structure](json-structure/prisma-access-browser-api-usage-report-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-access-browser-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-access-browser-api-browser-deployment-example.json)
- [Example](examples/prisma-access-browser-api-browser-deployment-request-example.json)
- [Example](examples/prisma-access-browser-api-browser-policy-example.json)
- [Example](examples/prisma-access-browser-api-browser-policy-request-example.json)
- [Example](examples/prisma-access-browser-api-browser-session-example.json)
- [Example](examples/prisma-access-browser-api-browser-user-example.json)
- [Example](examples/prisma-access-browser-api-managed-device-example.json)
- [Example](examples/prisma-access-browser-api-usage-report-example.json)

### SASE Tenancy Service API

A REST API for creating and managing Tenant Service Groups (TSGs) within the Palo Alto Networks SASE platform. The API supports building tenant hierarchies for multi-tenant deployments, managing TSG properties, and organizing service subscriptions across organizational units. Essential for managed security service providers and large enterprises with complex organizational structures. Uses OAuth 2.0 authentication.

- **Human URL:** [https://pan.dev/sase/api/tenancy/](https://pan.dev/sase/api/tenancy/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Multi-Tenant
- SASE
- Service Provider
- Tenant Management
- TSG

#### Properties

- [Documentation](https://pan.dev/sase/api/tenancy/)
- [OpenAPI](openapi/palo-alto-sase-tenancy-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sase-tenancy-api-tenant-service-group-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-tenancy-api-tenant-service-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-tenancy-api-tenant-service-group-update-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sase-tenancy-api-tenant-service-group-request-structure.json)
- [JSON Structure](json-structure/sase-tenancy-api-tenant-service-group-structure.json)
- [JSON Structure](json-structure/sase-tenancy-api-tenant-service-group-update-structure.json)
- [JSON-LD](json-ld/palo-alto-sase-tenancy-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/sase-tenancy-api-tenant-service-group-example.json)
- [Example](examples/sase-tenancy-api-tenant-service-group-request-example.json)
- [Example](examples/sase-tenancy-api-tenant-service-group-update-example.json)

### SASE IAM API

A REST API for managing identity and access on the SASE platform including creating service accounts, managing access policies, and configuring role-based access control for SASE API consumers. The API supports provisioning service account credentials used for OAuth 2.0 authentication across all SASE platform APIs. Part of the common SASE management services layer.

- **Human URL:** [https://pan.dev/sase/api/iam/](https://pan.dev/sase/api/iam/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Access Control
- Identity Management
- RBAC
- SASE
- Service Accounts

#### Properties

- [Documentation](https://pan.dev/sase/api/iam/)
- [OpenAPI](openapi/palo-alto-sase-iam-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sase-iam-api-access-policy-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-iam-api-access-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-iam-api-role-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-iam-api-service-account-credentials-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-iam-api-service-account-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-iam-api-service-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-iam-api-service-account-update-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sase-iam-api-access-policy-request-structure.json)
- [JSON Structure](json-structure/sase-iam-api-access-policy-structure.json)
- [JSON Structure](json-structure/sase-iam-api-role-structure.json)
- [JSON Structure](json-structure/sase-iam-api-service-account-credentials-structure.json)
- [JSON Structure](json-structure/sase-iam-api-service-account-request-structure.json)
- [JSON Structure](json-structure/sase-iam-api-service-account-structure.json)
- [JSON Structure](json-structure/sase-iam-api-service-account-update-structure.json)
- [JSON-LD](json-ld/palo-alto-sase-iam-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/sase-iam-api-access-policy-example.json)
- [Example](examples/sase-iam-api-access-policy-request-example.json)
- [Example](examples/sase-iam-api-role-example.json)
- [Example](examples/sase-iam-api-service-account-credentials-example.json)
- [Example](examples/sase-iam-api-service-account-example.json)
- [Example](examples/sase-iam-api-service-account-request-example.json)
- [Example](examples/sase-iam-api-service-account-update-example.json)

### SASE Subscription Service API

A REST API for managing license subscriptions assigned to Tenant Service Groups within the SASE platform. The API supports querying subscription entitlements, managing license allocations across tenant hierarchies, and retrieving subscription status information. Uses OAuth 2.0 authentication consistent with other SASE platform APIs.

- **Human URL:** [https://pan.dev/sase/api/subscription/](https://pan.dev/sase/api/subscription/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Entitlements
- Licensing
- SASE
- Subscriptions
- Tenant Management

#### Properties

- [Documentation](https://pan.dev/sase/api/subscription/)
- [OpenAPI](openapi/palo-alto-sase-subscription-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sase-subscription-api-allocation-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-subscription-api-allocation-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-subscription-api-entitlement-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-subscription-api-subscription-entitlements-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-subscription-api-subscription-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sase-subscription-api-allocation-entry-structure.json)
- [JSON Structure](json-structure/sase-subscription-api-allocation-request-structure.json)
- [JSON Structure](json-structure/sase-subscription-api-entitlement-structure.json)
- [JSON Structure](json-structure/sase-subscription-api-subscription-entitlements-structure.json)
- [JSON Structure](json-structure/sase-subscription-api-subscription-structure.json)
- [JSON-LD](json-ld/palo-alto-sase-subscription-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/sase-subscription-api-allocation-entry-example.json)
- [Example](examples/sase-subscription-api-allocation-request-example.json)
- [Example](examples/sase-subscription-api-entitlement-example.json)
- [Example](examples/sase-subscription-api-subscription-entitlements-example.json)
- [Example](examples/sase-subscription-api-subscription-example.json)

### SASE Aggregate Monitoring API

A REST API for performing aggregated monitoring queries across SASE tenants. The API supports querying application usage, threat data, URL categorization, and license utilization across all tenants in a hierarchy. Provides multi-tenant visibility for managed security service providers and enterprise administrators overseeing multiple organizational units.

- **Human URL:** [https://pan.dev/sase/api/mt-monitor/](https://pan.dev/sase/api/mt-monitor/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Analytics
- Monitoring
- Multi-Tenant
- SASE
- Threat Monitoring

#### Properties

- [Documentation](https://pan.dev/sase/api/mt-monitor/)
- [OpenAPI](openapi/palo-alto-sase-aggregate-monitoring-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sase-aggregate-monitoring-api-aggregation-query-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-aggregate-monitoring-api-aggregation-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-aggregate-monitoring-api-tenant-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sase-aggregate-monitoring-api-aggregation-query-structure.json)
- [JSON Structure](json-structure/sase-aggregate-monitoring-api-aggregation-response-structure.json)
- [JSON Structure](json-structure/sase-aggregate-monitoring-api-tenant-summary-structure.json)
- [JSON-LD](json-ld/palo-alto-sase-aggregate-monitoring-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/sase-aggregate-monitoring-api-aggregation-query-example.json)
- [Example](examples/sase-aggregate-monitoring-api-aggregation-response-example.json)
- [Example](examples/sase-aggregate-monitoring-api-tenant-summary-example.json)

### AIOps for NGFW BPA API

A REST API for the AIOps Best Practice Assessment service that programmatically generates firewall configuration assessments against Palo Alto Networks best practice recommendations. The API supports generating BPA data, checking report status, and retrieving assessment reports in JSON format. Available for both free and premium AIOps for NGFW instances. Helps identify configuration gaps and security improvement opportunities.

- **Human URL:** [https://pan.dev/aiops-ngfw-bpa/api/](https://pan.dev/aiops-ngfw-bpa/api/)
- **Base URL:** `https://api.example.com`

#### Tags

- AIOps
- Assessment
- Best Practices
- Configuration Analysis
- NGFW

#### Properties

- [Documentation](https://pan.dev/aiops-ngfw-bpa/api/)
- [OpenAPI](openapi/palo-alto-aiops-ngfw-bpa-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/aiops-ngfw-bpa-api-bpa-check-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aiops-ngfw-bpa-api-bpa-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aiops-ngfw-bpa-api-bpa-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aiops-ngfw-bpa-api-bpa-request-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/aiops-ngfw-bpa-api-bpa-check-structure.json)
- [JSON Structure](json-structure/aiops-ngfw-bpa-api-bpa-report-structure.json)
- [JSON Structure](json-structure/aiops-ngfw-bpa-api-bpa-request-status-structure.json)
- [JSON Structure](json-structure/aiops-ngfw-bpa-api-bpa-request-structure.json)
- [JSON-LD](json-ld/palo-alto-aiops-ngfw-bpa-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/aiops-ngfw-bpa-api-bpa-check-example.json)
- [Example](examples/aiops-ngfw-bpa-api-bpa-report-example.json)
- [Example](examples/aiops-ngfw-bpa-api-bpa-request-example.json)
- [Example](examples/aiops-ngfw-bpa-api-bpa-request-status-example.json)

### Strata Logging Service API

REST APIs for the Strata Logging Service (formerly Cortex Data Lake) providing log forwarding and query capabilities. The Log Forwarding API manages log forwarding profiles for syslog, HTTPS, and email destinations supporting CSV, LEEF, CEF, JSON, and PARQUET formats with up to 200 syslog destinations per instance. The Query Service API enables programmatic log retrieval and pagination across collected security telemetry data.

- **Human URL:** [https://pan.dev/cdl/docs/log-forwarding/](https://pan.dev/cdl/docs/log-forwarding/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Analytics
- Data Lake
- Log Forwarding
- Logging
- SIEM Integration

#### Properties

- [Documentation](https://pan.dev/cdl/docs/log-forwarding/)
- [Changelog](https://pan.dev/cdl/docs/logforwarding/release-notes/relnotes/)
- [OpenAPI](openapi/palo-alto-strata-logging-service-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/palo-alto-strata-logging-forwarding-asyncapi-original.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/strata-logging-forwarding-auth-log-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-forwarding-threat-log-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-forwarding-traffic-log-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-forwarding-url-log-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-forwarding-wildfire-log-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-service-api-email-destination-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-service-api-email-destination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-service-api-forwarding-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-service-api-https-destination-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-service-api-https-destination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-service-api-log-forwarding-profile-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-service-api-log-forwarding-profile-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-service-api-syslog-destination-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/strata-logging-service-api-syslog-destination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/strata-logging-forwarding-auth-log-payload-structure.json)
- [JSON Structure](json-structure/strata-logging-forwarding-threat-log-payload-structure.json)
- [JSON Structure](json-structure/strata-logging-forwarding-traffic-log-payload-structure.json)
- [JSON Structure](json-structure/strata-logging-forwarding-url-log-payload-structure.json)
- [JSON Structure](json-structure/strata-logging-forwarding-wildfire-log-payload-structure.json)
- [JSON Structure](json-structure/strata-logging-service-api-email-destination-request-structure.json)
- [JSON Structure](json-structure/strata-logging-service-api-email-destination-structure.json)
- [JSON Structure](json-structure/strata-logging-service-api-forwarding-status-structure.json)
- [JSON Structure](json-structure/strata-logging-service-api-https-destination-request-structure.json)
- [JSON Structure](json-structure/strata-logging-service-api-https-destination-structure.json)
- [JSON Structure](json-structure/strata-logging-service-api-log-forwarding-profile-request-structure.json)
- [JSON Structure](json-structure/strata-logging-service-api-log-forwarding-profile-structure.json)
- [JSON Structure](json-structure/strata-logging-service-api-syslog-destination-request-structure.json)
- [JSON Structure](json-structure/strata-logging-service-api-syslog-destination-structure.json)
- [JSON-LD](json-ld/palo-alto-strata-logging-forwarding-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/palo-alto-strata-logging-service-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/strata-logging-forwarding-auth-log-payload-example.json)
- [Example](examples/strata-logging-forwarding-threat-log-payload-example.json)
- [Example](examples/strata-logging-forwarding-traffic-log-payload-example.json)
- [Example](examples/strata-logging-forwarding-url-log-payload-example.json)
- [Example](examples/strata-logging-forwarding-wildfire-log-payload-example.json)
- [Example](examples/strata-logging-service-api-email-destination-example.json)
- [Example](examples/strata-logging-service-api-email-destination-request-example.json)
- [Example](examples/strata-logging-service-api-forwarding-status-example.json)
- [Example](examples/strata-logging-service-api-https-destination-example.json)
- [Example](examples/strata-logging-service-api-https-destination-request-example.json)
- [Example](examples/strata-logging-service-api-log-forwarding-profile-example.json)
- [Example](examples/strata-logging-service-api-log-forwarding-profile-request-example.json)
- [Example](examples/strata-logging-service-api-syslog-destination-example.json)
- [Example](examples/strata-logging-service-api-syslog-destination-request-example.json)

### Configuration Orchestration API

A REST API enabling third-party SD-WAN integration with Prisma Access Remote Networks. The API supports automated tunnel configuration, branch onboarding workflows, and coordination between third-party SD-WAN solutions and the Prisma Access SASE infrastructure. Designed for technology partners integrating their SD-WAN platforms with Palo Alto Networks SASE services.

- **Human URL:** [https://pan.dev/sase/api/config-orch/configuration-orchestration-api/](https://pan.dev/sase/api/config-orch/configuration-orchestration-api/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Remote Networks
- SASE
- SD-WAN Integration
- Third-Party
- Tunnel Configuration

#### Properties

- [Documentation](https://pan.dev/sase/api/config-orch/configuration-orchestration-api/)
- [OpenAPI](openapi/palo-alto-sase-config-orchestration-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sase-config-orchestration-api-bandwidth-allocation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-config-orchestration-api-i-psec-tunnel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-config-orchestration-api-ike-gateway-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-config-orchestration-api-ike-gateway-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-config-orchestration-api-onboarding-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-config-orchestration-api-prisma-access-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-config-orchestration-api-remote-network-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-config-orchestration-api-remote-network-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sase-config-orchestration-api-bandwidth-allocation-structure.json)
- [JSON Structure](json-structure/sase-config-orchestration-api-i-psec-tunnel-structure.json)
- [JSON Structure](json-structure/sase-config-orchestration-api-ike-gateway-config-structure.json)
- [JSON Structure](json-structure/sase-config-orchestration-api-ike-gateway-structure.json)
- [JSON Structure](json-structure/sase-config-orchestration-api-onboarding-status-structure.json)
- [JSON Structure](json-structure/sase-config-orchestration-api-prisma-access-location-structure.json)
- [JSON Structure](json-structure/sase-config-orchestration-api-remote-network-request-structure.json)
- [JSON Structure](json-structure/sase-config-orchestration-api-remote-network-structure.json)
- [JSON-LD](json-ld/palo-alto-sase-config-orchestration-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/sase-config-orchestration-api-bandwidth-allocation-example.json)
- [Example](examples/sase-config-orchestration-api-i-psec-tunnel-example.json)
- [Example](examples/sase-config-orchestration-api-ike-gateway-config-example.json)
- [Example](examples/sase-config-orchestration-api-ike-gateway-example.json)
- [Example](examples/sase-config-orchestration-api-onboarding-status-example.json)
- [Example](examples/sase-config-orchestration-api-prisma-access-location-example.json)
- [Example](examples/sase-config-orchestration-api-remote-network-example.json)
- [Example](examples/sase-config-orchestration-api-remote-network-request-example.json)

### Prisma Cloud DSPM API

A REST API for Data Security Posture Management within Prisma Cloud providing visibility and control over sensitive data stored across multi-cloud environments. The API supports data discovery, classification, and risk assessment for cloud data stores including databases, object storage, and file systems. Authentication uses JWT tokens consistent with the broader Prisma Cloud API framework.

- **Human URL:** [https://pan.dev/prisma-cloud/api/](https://pan.dev/prisma-cloud/api/)
- **Base URL:** `https://api.prismacloud.io`

#### Tags

- Classification
- Cloud Data
- Data Posture
- Data Security
- Multi-Cloud

#### Properties

- [Documentation](https://pan.dev/prisma-cloud/api/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-dspm-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/prisma-cloud-dspm-api-classification-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-dspm-api-data-asset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-dspm-api-data-risk-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-dspm-api-data-security-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-dspm-api-data-store-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-dspm-api-dspm-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-cloud-dspm-api-classification-structure.json)
- [JSON Structure](json-structure/prisma-cloud-dspm-api-data-asset-structure.json)
- [JSON Structure](json-structure/prisma-cloud-dspm-api-data-risk-structure.json)
- [JSON Structure](json-structure/prisma-cloud-dspm-api-data-security-alert-structure.json)
- [JSON Structure](json-structure/prisma-cloud-dspm-api-data-store-structure.json)
- [JSON Structure](json-structure/prisma-cloud-dspm-api-dspm-policy-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-cloud-dspm-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-cloud-dspm-api-classification-example.json)
- [Example](examples/prisma-cloud-dspm-api-data-asset-example.json)
- [Example](examples/prisma-cloud-dspm-api-data-risk-example.json)
- [Example](examples/prisma-cloud-dspm-api-data-security-alert-example.json)
- [Example](examples/prisma-cloud-dspm-api-data-store-example.json)
- [Example](examples/prisma-cloud-dspm-api-dspm-policy-example.json)

### SASE 5G Manage Services API

REST APIs for managing scalable, multi-tenant, agentless security for 5G networks. The API supports provisioning and configuring 5G security services that integrate with 5G authentication frameworks for securing mobile network traffic. Designed for telecommunications providers and enterprises deploying private 5G networks with Palo Alto Networks SASE security services.

- **Human URL:** [https://pan.dev/sase/api/manage-services-5g/](https://pan.dev/sase/api/manage-services-5g/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- 5G Security
- Agentless Security
- Mobile Network
- Multi-Tenant
- Telecommunications

#### Properties

- [Documentation](https://pan.dev/sase/api/manage-services-5g/)
- [OpenAPI](openapi/palo-alto-sase-5g-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sase-5g-api-network-slice-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-5g-api-network-slice-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-5g-api-security-metrics5-g-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-5g-api-security-policy5-g-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-5g-api-security-policy5-g-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-5g-api-tenant5-g-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-5g-api-tenant5-g-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sase-5g-api-network-slice-request-structure.json)
- [JSON Structure](json-structure/sase-5g-api-network-slice-structure.json)
- [JSON Structure](json-structure/sase-5g-api-security-metrics5-g-structure.json)
- [JSON Structure](json-structure/sase-5g-api-security-policy5-g-request-structure.json)
- [JSON Structure](json-structure/sase-5g-api-security-policy5-g-structure.json)
- [JSON Structure](json-structure/sase-5g-api-tenant5-g-request-structure.json)
- [JSON Structure](json-structure/sase-5g-api-tenant5-g-structure.json)
- [JSON-LD](json-ld/palo-alto-sase-5g-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/sase-5g-api-network-slice-example.json)
- [Example](examples/sase-5g-api-network-slice-request-example.json)
- [Example](examples/sase-5g-api-security-metrics5-g-example.json)
- [Example](examples/sase-5g-api-security-policy5-g-example.json)
- [Example](examples/sase-5g-api-security-policy5-g-request-example.json)
- [Example](examples/sase-5g-api-tenant5-g-example.json)
- [Example](examples/sase-5g-api-tenant5-g-request-example.json)

### Prisma AIRS AI Red Teaming API

An automated red teaming API for assessing the safety and security of generative AI systems including large language models and LLM-powered applications. The API simulates real-world threats by sending crafted attack prompts including jailbreaks, prompt injection, and input manipulation to target AI systems and evaluating responses. Supports creating scan targets, executing asynchronous vulnerability scans, and retrieving detailed reports.

- **Human URL:** [https://pan.dev/prisma-airs-redteam/api/ai-integration/introduction/](https://pan.dev/prisma-airs-redteam/api/ai-integration/introduction/)
- **Base URL:** `https://api.sase.paloaltonetworks.com/ai-red-teaming`

#### Tags

- AI Security
- GenAI
- LLM Security
- Red Teaming
- Vulnerability Assessment

#### Properties

- [Documentation](https://pan.dev/prisma-airs-redteam/api/ai-integration/introduction/)
- [Getting Started](https://docs.paloaltonetworks.com/ai-runtime-security/ai-red-teaming/identify-ai-system-risks-with-ai-red-teaming/get-started-with-prisma-airs-ai-red-teaming)
- [OpenAPI](openapi/palo-alto-prisma-airs-ai-red-teaming-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/prisma-airs-ai-red-teaming-api-attack-category-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-airs-ai-red-teaming-api-scan-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-airs-ai-red-teaming-api-scan-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-airs-ai-red-teaming-api-scan-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-airs-ai-red-teaming-api-scan-target-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-airs-ai-red-teaming-api-scan-target-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-airs-ai-red-teaming-api-vulnerability-finding-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-airs-ai-red-teaming-api-attack-category-structure.json)
- [JSON Structure](json-structure/prisma-airs-ai-red-teaming-api-scan-report-structure.json)
- [JSON Structure](json-structure/prisma-airs-ai-red-teaming-api-scan-request-structure.json)
- [JSON Structure](json-structure/prisma-airs-ai-red-teaming-api-scan-structure.json)
- [JSON Structure](json-structure/prisma-airs-ai-red-teaming-api-scan-target-request-structure.json)
- [JSON Structure](json-structure/prisma-airs-ai-red-teaming-api-scan-target-structure.json)
- [JSON Structure](json-structure/prisma-airs-ai-red-teaming-api-vulnerability-finding-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-airs-ai-red-teaming-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-airs-ai-red-teaming-api-attack-category-example.json)
- [Example](examples/prisma-airs-ai-red-teaming-api-scan-example.json)
- [Example](examples/prisma-airs-ai-red-teaming-api-scan-report-example.json)
- [Example](examples/prisma-airs-ai-red-teaming-api-scan-request-example.json)
- [Example](examples/prisma-airs-ai-red-teaming-api-scan-target-example.json)
- [Example](examples/prisma-airs-ai-red-teaming-api-scan-target-request-example.json)
- [Example](examples/prisma-airs-ai-red-teaming-api-vulnerability-finding-example.json)

### Identity Security Posture Management API

A REST API within the SaaS Security Posture Management framework providing security-related metrics and configurations for user and service accounts across SaaS environments. The API enables security teams to monitor, analyze, and respond to identity-related risks by connecting users, permissions, activities, and security configurations.

- **Human URL:** [https://pan.dev/sase/api/identity-sspm/](https://pan.dev/sase/api/identity-sspm/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Access Control
- Identity Security
- ITDR
- MFA
- SSPM

#### Properties

- [Documentation](https://pan.dev/sase/api/identity-sspm/)
- [OpenAPI](openapi/palo-alto-identity-security-posture-management-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/identity-security-posture-management-api-create-ticket-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-download-csv-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-feature-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-feature-state-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-idp-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-instant-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-list-response-idp-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-list-response-map-string-object-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-list-response-mfa-activity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-list-response-saa-s-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-list-response-saa-s-activity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-list-response-saa-s-instance-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-list-response-ticket-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-mfa-activity-count-by-app-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-mfa-activity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-remediation-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-saa-s-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-saa-s-activity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-saa-s-instance-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-ticket-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/identity-security-posture-management-api-unlink-ticket-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/identity-security-posture-management-api-create-ticket-request-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-download-csv-request-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-feature-state-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-feature-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-idp-info-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-instant-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-list-response-idp-info-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-list-response-map-string-object-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-list-response-mfa-activity-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-list-response-saa-s-account-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-list-response-saa-s-activity-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-list-response-saa-s-instance-info-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-list-response-ticket-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-mfa-activity-count-by-app-type-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-mfa-activity-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-remediation-request-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-saa-s-account-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-saa-s-activity-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-saa-s-instance-info-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-ticket-structure.json)
- [JSON Structure](json-structure/identity-security-posture-management-api-unlink-ticket-request-structure.json)
- [JSON-LD](json-ld/palo-alto-identity-security-posture-management-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/identity-security-posture-management-api-create-ticket-request-example.json)
- [Example](examples/identity-security-posture-management-api-download-csv-request-example.json)
- [Example](examples/identity-security-posture-management-api-feature-example.json)
- [Example](examples/identity-security-posture-management-api-feature-state-example.json)
- [Example](examples/identity-security-posture-management-api-idp-info-example.json)
- [Example](examples/identity-security-posture-management-api-instant-example.json)
- [Example](examples/identity-security-posture-management-api-list-response-idp-info-example.json)
- [Example](examples/identity-security-posture-management-api-list-response-map-string-object-example.json)
- [Example](examples/identity-security-posture-management-api-list-response-mfa-activity-example.json)
- [Example](examples/identity-security-posture-management-api-list-response-saa-s-account-example.json)
- [Example](examples/identity-security-posture-management-api-list-response-saa-s-activity-example.json)
- [Example](examples/identity-security-posture-management-api-list-response-saa-s-instance-info-example.json)
- [Example](examples/identity-security-posture-management-api-list-response-ticket-example.json)
- [Example](examples/identity-security-posture-management-api-mfa-activity-count-by-app-type-example.json)
- [Example](examples/identity-security-posture-management-api-mfa-activity-example.json)
- [Example](examples/identity-security-posture-management-api-remediation-request-example.json)
- [Example](examples/identity-security-posture-management-api-saa-s-account-example.json)
- [Example](examples/identity-security-posture-management-api-saa-s-activity-example.json)
- [Example](examples/identity-security-posture-management-api-saa-s-instance-info-example.json)
- [Example](examples/identity-security-posture-management-api-ticket-example.json)
- [Example](examples/identity-security-posture-management-api-unlink-ticket-request-example.json)

### SASE 5G Monitor Services API

REST APIs for monitoring 5G security services within the SASE platform. Provides telemetry, analytics, and health monitoring data for 5G network security deployments. Complements the SASE 5G Manage Services API by providing visibility into security service performance, traffic patterns, and threat detection metrics across 5G network environments. Uses OAuth 2.0 authentication.

- **Human URL:** [https://pan.dev/sase/api/monitor-services-5g/](https://pan.dev/sase/api/monitor-services-5g/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- 5G Security
- Monitoring
- Multi-Tenant
- Network Analytics
- Telecommunications

#### Properties

- [Documentation](https://pan.dev/sase/api/monitor-services-5g/)
- [OpenAPI](openapi/palo-alto-sase-5g-monitor-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sase-5g-monitor-api-count-filter-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-5g-monitor-api-incidents-count-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-5g-monitor-api-mapping-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-5g-monitor-api-throughput-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-5g-monitor-api-trend-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sase-5g-monitor-api-count-filter-request-structure.json)
- [JSON Structure](json-structure/sase-5g-monitor-api-incidents-count-request-structure.json)
- [JSON Structure](json-structure/sase-5g-monitor-api-mapping-request-structure.json)
- [JSON Structure](json-structure/sase-5g-monitor-api-throughput-request-structure.json)
- [JSON Structure](json-structure/sase-5g-monitor-api-trend-request-structure.json)
- [JSON-LD](json-ld/palo-alto-sase-5g-monitor-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/sase-5g-monitor-api-count-filter-request-example.json)
- [Example](examples/sase-5g-monitor-api-incidents-count-request-example.json)
- [Example](examples/sase-5g-monitor-api-mapping-request-example.json)
- [Example](examples/sase-5g-monitor-api-throughput-request-example.json)
- [Example](examples/sase-5g-monitor-api-trend-request-example.json)

### Prisma SASE Service Status API

A public JSON API for monitoring Prisma SASE service health and status built on the Atlassian StatusPage platform. Provides endpoints for overall service status, individual component health, unresolved and recent incidents, and upcoming and active scheduled maintenance windows. Returns status indicators including operational, degraded performance, partial outage, and major outage. No authentication required.

- **Human URL:** [https://pan.dev/sase/docs/saseservicestatusapi/](https://pan.dev/sase/docs/saseservicestatusapi/)
- **Base URL:** `https://sase.status.paloaltonetworks.com/api/v2`

#### Tags

- Incidents
- Maintenance
- Monitoring
- SASE
- Status

#### Properties

- [Documentation](https://pan.dev/sase/docs/saseservicestatusapi/)
- [Postman Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cross-Platform Service Status API

A public JSON API for monitoring the status of all Palo Alto Networks cloud services and products built on the Atlassian StatusPage platform. Provides endpoints for portfolio-wide status, individual product and service component health, unresolved and recent incidents, and scheduled maintenance events. Component statuses include operational, degraded performance, partial outage, and major outage. No authentication required.

- **Human URL:** [https://pan.dev/cross-platform/docs/servicestatusapi/](https://pan.dev/cross-platform/docs/servicestatusapi/)
- **Base URL:** `https://status.paloaltonetworks.com/api/v2`

#### Tags

- Incidents
- Maintenance
- Monitoring
- Platform Health
- Status

#### Properties

- [Documentation](https://pan.dev/cross-platform/docs/servicestatusapi/)
- [Postman Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SASE Authentication Service API

The OAuth 2.0 authentication service that provides access tokens for all Prisma SASE platform APIs. Uses Client ID and Client Secret credentials to generate short-lived bearer tokens with a 15-minute lifespan. All SASE platform APIs including Prisma Access, SD-WAN, SSPM, and management services require tokens from this endpoint. Supports tenant service group (TSG) scoping for multi-tenant environments.

- **Human URL:** [https://pan.dev/sase/api/auth/](https://pan.dev/sase/api/auth/)
- **Base URL:** `https://auth.apps.paloaltonetworks.com`

#### Tags

- Access Tokens
- Authentication
- Identity
- OAuth 2.0
- SASE

#### Properties

- [Documentation](https://pan.dev/sase/api/auth/)
- [Getting Started](https://pan.dev/sase/docs/getstarted/)
- [Postman Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Expedition API (Deprecated)

A RESTful API for the Expedition 2.0 migration tool enabling programmatic firewall configuration migration from third-party vendors, policy optimization, and rule analysis. Supported migration from Check Point, Cisco ASA, Fortinet, and other firewall platforms to PAN-OS. Built on the Laravel PHP framework. Expedition reached end-of-support in January 2025. Developers should use Strata Cloud Manager migration tools for new migration workflows.

- **Human URL:** [https://pan.dev/expedition/docs/expedition_apiint/](https://pan.dev/expedition/docs/expedition_apiint/)
- **Base URL:** `https://{expedition-vm-ip}/api/v1/`

#### Tags

- Configuration
- Deprecated
- Firewall
- Migration
- Policy Optimization

#### Properties

- [Documentation](https://pan.dev/expedition/docs/expedition_apiint/)
- [Getting Started](https://pan.dev/expedition/docs/expedition_workflow/)
- [Postman Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SASE Multitenant Notifications API

A REST API for managing notifications and notification profiles across SASE multitenant environments. Supports creating and managing notification profiles, configuring webhook destinations, testing webhook connectivity, and retrieving notifications for security incidents, platform announcements, Prisma Access dataplane upgrades, and certificate expiry warnings across tenant hierarchies. Uses OAuth 2.0 authentication.

- **Human URL:** [https://pan.dev/sase/api/mt-notifications/](https://pan.dev/sase/api/mt-notifications/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Alerts
- Multi-Tenant
- Notifications
- SASE
- Webhooks

#### Properties

- [Documentation](https://pan.dev/sase/api/mt-notifications/)
- [OpenAPI](openapi/palo-alto-sase-multitenant-notifications-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-email-channel-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-email-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-mt-notif-agg-key-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-mt-notification-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-mt-notification-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-notif-category-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-notif-channel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-notif-filter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-notif-list-api-req-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-notif-profile-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-notif-profile-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-notif-read-state-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-notif-state-change-api-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-notif-sub-category-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-notif-type-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-sort-by-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-notifications-api-webhook-channel-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-email-channel-details-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-email-details-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-mt-notif-agg-key-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-mt-notification-list-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-mt-notification-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-notif-category-detail-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-notif-channel-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-notif-filter-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-notif-list-api-req-body-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-notif-profile-list-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-notif-profile-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-notif-read-state-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-notif-state-change-api-body-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-notif-sub-category-detail-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-notif-type-detail-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-sort-by-structure.json)
- [JSON Structure](json-structure/sase-multitenant-notifications-api-webhook-channel-details-structure.json)
- [JSON-LD](json-ld/palo-alto-sase-multitenant-notifications-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/sase-multitenant-notifications-api-email-channel-details-example.json)
- [Example](examples/sase-multitenant-notifications-api-email-details-example.json)
- [Example](examples/sase-multitenant-notifications-api-mt-notif-agg-key-example.json)
- [Example](examples/sase-multitenant-notifications-api-mt-notification-example.json)
- [Example](examples/sase-multitenant-notifications-api-mt-notification-list-example.json)
- [Example](examples/sase-multitenant-notifications-api-notif-category-detail-example.json)
- [Example](examples/sase-multitenant-notifications-api-notif-channel-example.json)
- [Example](examples/sase-multitenant-notifications-api-notif-filter-example.json)
- [Example](examples/sase-multitenant-notifications-api-notif-list-api-req-body-example.json)
- [Example](examples/sase-multitenant-notifications-api-notif-profile-example.json)
- [Example](examples/sase-multitenant-notifications-api-notif-profile-list-example.json)
- [Example](examples/sase-multitenant-notifications-api-notif-read-state-example.json)
- [Example](examples/sase-multitenant-notifications-api-notif-state-change-api-body-example.json)
- [Example](examples/sase-multitenant-notifications-api-notif-sub-category-detail-example.json)
- [Example](examples/sase-multitenant-notifications-api-notif-type-detail-example.json)
- [Example](examples/sase-multitenant-notifications-api-sort-by-example.json)
- [Example](examples/sase-multitenant-notifications-api-webhook-channel-details-example.json)
- [JSON Schema](json-schema/sase-notifications-announcement-notification-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-notifications-certificate-expiry-notification-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-notifications-dataplane-upgrade-notification-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-notifications-incident-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-notifications-incident-notification-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-notifications-service-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-notifications-tenant-context-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sase-notifications-announcement-notification-structure.json)
- [JSON Structure](json-structure/sase-notifications-certificate-expiry-notification-structure.json)
- [JSON Structure](json-structure/sase-notifications-dataplane-upgrade-notification-structure.json)
- [JSON Structure](json-structure/sase-notifications-incident-detail-structure.json)
- [JSON Structure](json-structure/sase-notifications-incident-notification-structure.json)
- [JSON Structure](json-structure/sase-notifications-service-info-structure.json)
- [JSON Structure](json-structure/sase-notifications-tenant-context-structure.json)
- [Example](examples/sase-notifications-announcement-notification-example.json)
- [Example](examples/sase-notifications-certificate-expiry-notification-example.json)
- [Example](examples/sase-notifications-dataplane-upgrade-notification-example.json)
- [Example](examples/sase-notifications-incident-detail-example.json)
- [Example](examples/sase-notifications-incident-notification-example.json)
- [Example](examples/sase-notifications-service-info-example.json)
- [Example](examples/sase-notifications-tenant-context-example.json)
- [JSON-LD](json-ld/palo-alto-sase-notifications-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### SASE Multitenant Interconnect API

A REST API for managing service provider interconnect configurations within the SASE platform. Enables using service provider backbones for directing Prisma Access egress traffic instead of relying on public cloud providers. Supports managing traffic routing preferences on a per-service-provider and per-region basis for telecommunications partners including BT, Orange, and AT&T. Uses OAuth 2.0 authentication.

- **Human URL:** [https://pan.dev/sase/api/mt-interconnect/multitenant-interconnect-apis/](https://pan.dev/sase/api/mt-interconnect/multitenant-interconnect-apis/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Interconnect
- Multi-Tenant
- Network Routing
- SASE
- Service Provider

#### Properties

- [Documentation](https://pan.dev/sase/api/mt-interconnect/multitenant-interconnect-apis/)
- [OpenAPI](openapi/palo-alto-sase-multitenant-interconnect-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-bandwidth-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-cloud-provider-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-connection-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-dedicated-vlan-attachment-details-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-interconnect-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-interconnect-usage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-ip-block-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-ip-block-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-ip-pool-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-ip-provider-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-physical-connection-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-physical-interconnect-link-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-session-initialization-mode-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-settings-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-stack-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-vlan-attachment-custom-ip-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sase-multitenant-interconnect-api-vlan-attachment-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-bandwidth-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-cloud-provider-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-connection-type-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-dedicated-vlan-attachment-details-entry-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-interconnect-request-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-interconnect-usage-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-ip-block-entry-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-ip-block-type-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-ip-pool-request-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-ip-provider-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-physical-connection-entry-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-physical-interconnect-link-type-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-session-initialization-mode-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-settings-entry-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-stack-type-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-vlan-attachment-custom-ip-address-structure.json)
- [JSON Structure](json-structure/sase-multitenant-interconnect-api-vlan-attachment-request-structure.json)
- [JSON-LD](json-ld/palo-alto-sase-multitenant-interconnect-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/sase-multitenant-interconnect-api-bandwidth-example.json)
- [Example](examples/sase-multitenant-interconnect-api-cloud-provider-example.json)
- [Example](examples/sase-multitenant-interconnect-api-connection-type-example.json)
- [Example](examples/sase-multitenant-interconnect-api-dedicated-vlan-attachment-details-entry-example.json)
- [Example](examples/sase-multitenant-interconnect-api-interconnect-request-example.json)
- [Example](examples/sase-multitenant-interconnect-api-interconnect-usage-example.json)
- [Example](examples/sase-multitenant-interconnect-api-ip-block-entry-example.json)
- [Example](examples/sase-multitenant-interconnect-api-ip-block-type-example.json)
- [Example](examples/sase-multitenant-interconnect-api-ip-pool-request-example.json)
- [Example](examples/sase-multitenant-interconnect-api-ip-provider-example.json)
- [Example](examples/sase-multitenant-interconnect-api-physical-connection-entry-example.json)
- [Example](examples/sase-multitenant-interconnect-api-physical-interconnect-link-type-example.json)
- [Example](examples/sase-multitenant-interconnect-api-session-initialization-mode-example.json)
- [Example](examples/sase-multitenant-interconnect-api-settings-entry-example.json)
- [Example](examples/sase-multitenant-interconnect-api-stack-type-example.json)
- [Example](examples/sase-multitenant-interconnect-api-vlan-attachment-custom-ip-address-example.json)
- [Example](examples/sase-multitenant-interconnect-api-vlan-attachment-request-example.json)

### Cloud Identity Engine API

A REST API for the Cloud Identity Engine (CIE) Directory Sync Service that aggregates, normalizes, and provides access to enterprise identity data from multiple directory sources through a unified API. Supports synchronization of user, group, and organizational unit data from Active Directory, Azure Active Directory, Okta, Google Workspace, and PingFederate. Provides enriched user context including device, location, and logon event data for identity-aware security policies.

- **Human URL:** [https://pan.dev/scm/api/config/ciedss/ciedss/](https://pan.dev/scm/api/config/ciedss/ciedss/)
- **Base URL:** `https://api.strata.paloaltonetworks.com`

#### Tags

- Active Directory
- Azure AD
- Cloud Identity
- Directory Sync
- Identity

#### Properties

- [Documentation](https://pan.dev/scm/api/config/ciedss/ciedss/)
- [Getting Started](https://pan.dev/scm/docs/getstarted/)
- [OpenAPI](openapi/palo-alto-cloud-identity-engine-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/cloud-identity-engine-api-attr_based_filter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-check_group_membership-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-check_user_in_particular_group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-domain_param-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-fetch_all_users_attrs-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-group_filter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-list_all_groups_in_domain-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-list_all_users_in_domain-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-list_groups_user_belongs_to-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-list_specific_groups-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-list_specific_users-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-list_users_in_particular_group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloud-identity-engine-api-pagination_params-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/cloud-identity-engine-api-attr_based_filter-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-check_group_membership-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-check_user_in_particular_group-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-domain_param-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-fetch_all_users_attrs-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-group_filter-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-list_all_groups_in_domain-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-list_all_users_in_domain-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-list_groups_user_belongs_to-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-list_specific_groups-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-list_specific_users-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-list_users_in_particular_group-structure.json)
- [JSON Structure](json-structure/cloud-identity-engine-api-pagination_params-structure.json)
- [JSON-LD](json-ld/palo-alto-cloud-identity-engine-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/cloud-identity-engine-api-attr_based_filter-example.json)
- [Example](examples/cloud-identity-engine-api-check_group_membership-example.json)
- [Example](examples/cloud-identity-engine-api-check_user_in_particular_group-example.json)
- [Example](examples/cloud-identity-engine-api-domain_param-example.json)
- [Example](examples/cloud-identity-engine-api-fetch_all_users_attrs-example.json)
- [Example](examples/cloud-identity-engine-api-group_filter-example.json)
- [Example](examples/cloud-identity-engine-api-list_all_groups_in_domain-example.json)
- [Example](examples/cloud-identity-engine-api-list_all_users_in_domain-example.json)
- [Example](examples/cloud-identity-engine-api-list_groups_user_belongs_to-example.json)
- [Example](examples/cloud-identity-engine-api-list_specific_groups-example.json)
- [Example](examples/cloud-identity-engine-api-list_specific_users-example.json)
- [Example](examples/cloud-identity-engine-api-list_users_in_particular_group-example.json)
- [Example](examples/cloud-identity-engine-api-pagination_params-example.json)

### Prisma Cloud MSSP API

A REST API enabling Managed Security Service Providers to manage multi-tenant security operations at scale within Prisma Cloud. The API provides endpoints for policy group and tenant group management, user account administration, license usage tracking, tenant lifecycle operations, stack mapping, and proxy endpoint provisioning. Authentication uses JWT-based bearer tokens supporting both service-to-service and user-to-service authentication schemes.

- **Human URL:** [https://pan.dev/prisma-cloud/api/mssp/prisma-cloud-managed-security-service-provider-mssp/](https://pan.dev/prisma-cloud/api/mssp/prisma-cloud-managed-security-service-provider-mssp/)
- **Base URL:** `https://api.prismacloud.io`

#### Tags

- Cloud Security
- Licensing
- Managed Services
- MSSP
- Multi-Tenant

#### Properties

- [Documentation](https://pan.dev/prisma-cloud/api/mssp/prisma-cloud-managed-security-service-provider-mssp/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-mssp-api-openapi-original.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-change-password-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-contact-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-create-managed-tenant-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-create-mssp-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-create-policy-group-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-create-tenant-group-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-form-login-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-form-login-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-jwk-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-jwks-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-license-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-license-pool-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-managed-tenant-detailed-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-managed-tenant-license-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-managed-tenant-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-managed-tenants-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-module-info-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-module-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-mssp-license-info-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-mssp-license-pool-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-mssp-license-pool-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-mssp-license-pools-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-mssp-license-usage-request-object-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-mssp-license-usage-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-mssp-list-user-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-mssp-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-mssp-user-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-mssp-user-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-operation-ack-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-operation-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-operations-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-policy-group-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-policy-group-list-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-policy-group-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-policy-group-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-policy-groups-list-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-recur-string-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-relative-time-duration-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-relative-time-range-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-schedule-task-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-seamless-login-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-stack-mapping-plan-types-list-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-stack-mapping-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-change-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-group-license-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-group-mapping-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-group-policy-group-map-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-group-policy-group-mapping-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-group-policy-group-mapping-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-group-policy-group-mappings-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-group-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-groups-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-ids-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-license-usage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-tenant-update-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-time-range-config-object-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-to-now-time-range-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-token-refresh-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-update-managed-tenant-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-update-mssp-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-update-tenant-group-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-v1-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-validate-token-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-cloud-mssp-api-validate-token-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-change-password-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-contact-info-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-create-managed-tenant-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-create-mssp-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-create-policy-group-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-create-tenant-group-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-form-login-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-form-login-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-jwk-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-jwks-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-license-info-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-license-pool-info-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-managed-tenant-detailed-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-managed-tenant-license-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-managed-tenant-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-managed-tenants-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-module-info-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-module-info-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-mssp-license-info-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-mssp-license-pool-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-mssp-license-pool-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-mssp-license-pools-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-mssp-license-usage-request-object-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-mssp-license-usage-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-mssp-list-user-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-mssp-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-mssp-user-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-mssp-user-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-operation-ack-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-operation-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-operations-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-policy-group-info-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-policy-group-list-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-policy-group-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-policy-group-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-policy-groups-list-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-recur-string-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-relative-time-duration-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-relative-time-range-config-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-schedule-task-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-seamless-login-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-stack-mapping-plan-types-list-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-stack-mapping-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-task-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-change-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-group-license-info-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-group-mapping-details-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-group-policy-group-map-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-group-policy-group-mapping-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-group-policy-group-mapping-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-group-policy-group-mappings-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-group-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-groups-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-ids-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-license-usage-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-tenant-update-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-time-range-config-object-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-to-now-time-range-config-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-token-refresh-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-update-managed-tenant-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-update-mssp-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-update-tenant-group-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-v1-response-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-validate-token-request-structure.json)
- [JSON Structure](json-structure/prisma-cloud-mssp-api-validate-token-response-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-cloud-mssp-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-cloud-mssp-api-change-password-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-contact-info-example.json)
- [Example](examples/prisma-cloud-mssp-api-create-managed-tenant-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-create-mssp-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-create-policy-group-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-create-tenant-group-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-form-login-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-form-login-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-jwk-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-jwks-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-license-info-example.json)
- [Example](examples/prisma-cloud-mssp-api-license-pool-info-example.json)
- [Example](examples/prisma-cloud-mssp-api-managed-tenant-detailed-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-managed-tenant-license-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-managed-tenant-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-managed-tenants-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-module-info-example.json)
- [Example](examples/prisma-cloud-mssp-api-module-info-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-mssp-license-info-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-mssp-license-pool-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-mssp-license-pool-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-mssp-license-pools-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-mssp-license-usage-request-object-example.json)
- [Example](examples/prisma-cloud-mssp-api-mssp-license-usage-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-mssp-list-user-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-mssp-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-mssp-user-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-mssp-user-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-operation-ack-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-operation-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-operations-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-policy-group-info-example.json)
- [Example](examples/prisma-cloud-mssp-api-policy-group-list-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-policy-group-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-policy-group-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-policy-groups-list-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-recur-string-example.json)
- [Example](examples/prisma-cloud-mssp-api-relative-time-duration-example.json)
- [Example](examples/prisma-cloud-mssp-api-relative-time-range-config-example.json)
- [Example](examples/prisma-cloud-mssp-api-schedule-task-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-seamless-login-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-stack-mapping-plan-types-list-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-stack-mapping-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-task-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-change-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-group-license-info-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-group-mapping-details-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-group-policy-group-map-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-group-policy-group-mapping-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-group-policy-group-mapping-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-group-policy-group-mappings-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-group-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-groups-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-ids-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-license-usage-example.json)
- [Example](examples/prisma-cloud-mssp-api-tenant-update-example.json)
- [Example](examples/prisma-cloud-mssp-api-time-range-config-object-example.json)
- [Example](examples/prisma-cloud-mssp-api-to-now-time-range-config-example.json)
- [Example](examples/prisma-cloud-mssp-api-token-refresh-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-update-managed-tenant-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-update-mssp-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-update-tenant-group-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-v1-response-example.json)
- [Example](examples/prisma-cloud-mssp-api-validate-token-request-example.json)
- [Example](examples/prisma-cloud-mssp-api-validate-token-response-example.json)

### VM-Series Licensing API

A REST API for licensing VM-Series virtual firewalls that do not have direct internet access to the Palo Alto Networks license server. Supports automated license activation, deactivation, and management for VM-Series deployments across private clouds and air-gapped environments. Enables integration with orchestration platforms for automated firewall provisioning and license lifecycle management.

- **Human URL:** [https://docs.paloaltonetworks.com/vm-series/10-2/vm-series-deployment/license-the-vm-series-firewall/vm-series-models/licensing-api](https://docs.paloaltonetworks.com/vm-series/10-2/vm-series-deployment/license-the-vm-series-firewall/vm-series-models/licensing-api)
- **Base URL:** `https://licensing.paloaltonetworks.com`

#### Tags

- Automation
- Firewall
- Licensing
- Virtualization
- VM-Series

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/vm-series/10-2/vm-series-deployment/license-the-vm-series-firewall/vm-series-models/licensing-api)
- [Postman Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/palo-alto-prisma-cloud-mssp-api-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prisma Access Insights API

A REST API for querying the health and performance of Prisma Access network deployments across multiple API versions (v1.0, v2.0, v3.0). Supports data resource queries for tunnel status, bandwidth utilization, connected user analytics, site health, accelerated application performance, and PAB events. Available for both cloud-managed (TSG-based) and Panorama-managed Prisma Access customers. Uses OAuth 2.0 bearer token authentication consistent with the SASE platform.

- **Human URL:** [https://pan.dev/access/api/insights/](https://pan.dev/access/api/insights/)
- **Base URL:** `https://api.sase.paloaltonetworks.com`

#### Tags

- Analytics
- Monitoring
- Network Health
- Prisma Access
- SASE

#### Properties

- [Documentation](https://pan.dev/access/api/insights/)
- [API Reference](https://pan.dev/access/api/insights/1.0/)
- [API Reference](https://pan.dev/access/api/insights/2.0/)
- [API Reference](https://pan.dev/access/api/insights/3.0/)
- [Getting Started](https://pan.dev/sase/docs/getstarted/)
- [OpenAPI](openapi/palo-alto-prisma-access-insights-api-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/prisma-access-insights-api-custom-query-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-insights-api-data-resource-query-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-insights-api-data-resource-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-insights-api-export-job-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-insights-api-export-job-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-insights-api-query-filter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/prisma-access-insights-api-time-range-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/prisma-access-insights-api-custom-query-structure.json)
- [JSON Structure](json-structure/prisma-access-insights-api-data-resource-query-structure.json)
- [JSON Structure](json-structure/prisma-access-insights-api-data-resource-response-structure.json)
- [JSON Structure](json-structure/prisma-access-insights-api-export-job-response-structure.json)
- [JSON Structure](json-structure/prisma-access-insights-api-export-job-status-structure.json)
- [JSON Structure](json-structure/prisma-access-insights-api-query-filter-structure.json)
- [JSON Structure](json-structure/prisma-access-insights-api-time-range-structure.json)
- [JSON-LD](json-ld/palo-alto-prisma-access-insights-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/prisma-access-insights-api-custom-query-example.json)
- [Example](examples/prisma-access-insights-api-data-resource-query-example.json)
- [Example](examples/prisma-access-insights-api-data-resource-response-example.json)
- [Example](examples/prisma-access-insights-api-export-job-response-example.json)
- [Example](examples/prisma-access-insights-api-export-job-status-example.json)
- [Example](examples/prisma-access-insights-api-query-filter-example.json)
- [Example](examples/prisma-access-insights-api-time-range-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://pan.dev/)
- [Documentation](https://docs.paloaltonetworks.com/)
- [Documentation](https://docs.paloaltonetworks.com/develop/api)
- [Website](https://www.paloaltonetworks.com)
- [Support](https://www.paloaltonetworks.com/services/support)
- [Blog](https://www.paloaltonetworks.com/blog/)
- [Blog R S S](https://www.paloaltonetworks.com/blog/feed/)
- [Status Page](https://status.paloaltonetworks.com/)
- [Forum](https://live.paloaltonetworks.com/)
- [Security](https://security.paloaltonetworks.com/)
- [GitHub Organization](https://github.com/PaloAltoNetworks)
- [GitHub Organization](https://github.com/demisto)
- [GitHub Organization](https://github.com/pan-unit42)
- [GitHub Repository](https://github.com/PaloAltoNetworks/pan-os-python)
- [GitHub Repository](https://github.com/PaloAltoNetworks/pango)
- [GitHub Repository](https://github.com/PaloAltoNetworks/pan-python)
- [GitHub Repository](https://github.com/PaloAltoNetworks/pan-os-php)
- [SDK](https://github.com/PaloAltoNetworks/prisma-sase-sdk-python)
- [SDK](https://github.com/PaloAltoNetworks/cortex-cloud-go)
- [SDK](https://github.com/PaloAltoNetworks/cloud-ngfw-aws-go)
- [C L I](https://github.com/PaloAltoNetworks/homebrew-cortexcli)
- [C L I](https://github.com/PaloAltoNetworks/upgrade-assurance-cli)
- [Terraform Provider](https://registry.terraform.io/providers/PaloAltoNetworks/panos/latest)
- [Terraform Provider](https://registry.terraform.io/providers/PaloAltoNetworks/scm/latest)
- [Terraform Provider](https://registry.terraform.io/providers/PaloAltoNetworks/cortexcloud/latest)
- [Terraform Provider](https://registry.terraform.io/providers/PaloAltoNetworks/prismasdwan/latest)
- [Tools](https://github.com/PaloAltoNetworks/pan-os-upgrade-assurance)
- [Tools](https://github.com/PaloAltoNetworks/prisma-cloud-scan)
- [Tools](https://github.com/PaloAltoNetworks/cobra-tool)
- [Portal](https://gallery.pan.dev/)
- [Terraform Provider](https://registry.terraform.io/namespaces/PaloAltoNetworks)
- [Terraform Provider](https://registry.terraform.io/providers/PaloAltoNetworks/cloudngfwaws/latest)
- [Terraform Provider](https://registry.terraform.io/providers/PaloAltoNetworks/prismacloud/latest)
- [Terraform Provider](https://registry.terraform.io/providers/PaloAltoNetworks/prismacloudcompute/latest)
- [Ansible Collection](https://galaxy.ansible.com/paloaltonetworks/panos)
- [Training](https://www.paloaltonetworks.com/services/education)
- [Training](https://learn.paloaltonetworks.com)
- [Privacy Policy](https://www.paloaltonetworks.com/legal/privacy)
- [Terms of Service](https://www.paloaltonetworks.com/legal)
- [JSON-LD](json-ld/palo-alto-networks-security-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [AsyncAPI](asyncapi/palo-alto-sase-notifications-asyncapi-original.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [X (Twitter)](https://x.com/PaloAltoNtwks)
- [YouTube](https://www.youtube.com/@pabornetworks)
- [LinkedIn](https://www.linkedin.com/company/palo-alto-networks)
- [Blog](https://medium.com/palo-alto-networks-developer-blog)
- [Blog R S S](https://medium.com/feed/palo-alto-networks-developer-blog)
- [Release Notes](https://docs.paloaltonetworks.com/release-notes)
- [Changelog](https://pan.dev/sase/docs/release-notes/changelog/)
- [Changelog](https://pan.dev/scm/docs/release-notes/changelog/)
- [Postman Workspace](https://www.postman.com/paloaltonetworks)
- [Slack](https://start.paloaltonetworks.com/join-our-slack-community)
- [Blog](https://unit42.paloaltonetworks.com/)
- [Blog R S S](https://unit42.paloaltonetworks.com/feed/)
- [Portal](https://cortex.pan.dev/)
- [Portal](https://xsoar.pan.dev/)
- [Documentation](https://pan.dev/swfw/)
- [Integrations Application](https://splunkbase.splunk.com/app/2757)
- [Partner](https://www.paloaltonetworks.com/partners)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [Spectral Rules](rules/palo-alto-networks-spectral-rules.yml)
- [Vocabulary](vocabulary/palo-alto-networks-vocabulary.yaml)
- [JSON-LD](json-ld/palo-alto-networks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://www.paloaltonetworks.com/partners)
- [M C P Server](https://github.com/PaloAltoNetworks/pan-mcp-relay)

## Maintainers

**Email:** kin@apievangelist.com
