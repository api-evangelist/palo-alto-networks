# Palo Alto Networks (palo-alto-networks)
Palo Alto Networks is a global cybersecurity leader providing advanced security platforms across network security, cloud security, and security operations. Its developer platform at pan.dev offers APIs for PAN-OS firewalls, Prisma Cloud, Prisma Access/SD-WAN, Cortex XDR/XSOAR/XSIAM, and cloud-delivered security services.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Cybersecurity, Firewall, Cloud Security, Threat Intelligence, Network Security, SASE, XDR, SOAR

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-03-01

## APIs

### PAN-OS REST API
A RESTful API for managing PAN-OS next-generation firewalls including security policies, network objects, address groups, and device configuration. The REST API provides simplified JSON-based access to common firewall operations as an alternative to the XML API. Supports CRUD operations on policy rules, address objects, service objects, and security profiles. Authentication uses API keys generated from the firewall management interface or via the XML API keygen command.

**Human URL:** [https://pan.dev/panos/docs/restapi/](https://pan.dev/panos/docs/restapi/)


#### Tags:

 - Firewall, Network Security, Configuration, REST API, Policies

#### Properties

- [Documentation](https://pan.dev/panos/docs/restapi/)
- [GettingStarted](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-rest-api)
- [APIReference](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/pan-os-rest-api-reference)
- [Authentication](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-rest-api/get-your-api-key)

### PAN-OS XML API
The comprehensive XML-based API for PAN-OS providing full access to all firewall configuration, operational commands, reporting, logging, and commit operations. Supports request types including keygen for authentication, config for configuration changes using XPath, op for operational commands, report for generating reports, log for retrieving traffic and threat logs, and user-id for dynamic user-to-IP mapping. The XML API covers the complete feature set of PAN-OS and is the foundation that the REST API is built upon.

**Human URL:** [https://pan.dev/panos/docs/xmlapi/](https://pan.dev/panos/docs/xmlapi/)


#### Tags:

 - Firewall, XML, Configuration, Monitoring, Operations

#### Properties

- [Documentation](https://pan.dev/panos/docs/xmlapi/)
- [GettingStarted](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-xml-api)
- [APIReference](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/pan-os-xml-api-request-types)

### Panorama API
The Panorama API uses the same PAN-OS XML and REST API interfaces but provides centralized management of multiple firewalls from a single management server. Supports device group and template stack operations for pushing configuration to managed firewalls, centralized logging and reporting, and multi-device commit workflows. Panorama-specific API operations include managing device groups, template stacks, log collectors, and performing push operations to managed devices.

**Human URL:** [https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api)


#### Tags:

 - Centralized Management, Orchestration, Firewall, Device Groups, Templates

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api)
- [APIReference](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api)

### Strata Cloud Manager API
A unified cloud-based API for managing Palo Alto Networks next-generation firewalls and SASE from a single management plane. Strata Cloud Manager provides configuration management for security policies, network objects, and device settings across hardware, virtual, and cloud-native firewalls. The API uses OAuth 2.0 authentication with bearer tokens and provides RESTful endpoints for policy lifecycle management, object CRUD operations, and deployment workflows.

**Human URL:** [https://pan.dev/scm/docs/home/](https://pan.dev/scm/docs/home/)


#### Tags:

 - Cloud Management, NGFW, SASE, Configuration, Unified Management

#### Properties

- [Documentation](https://pan.dev/scm/docs/home/)
- [APIReference](https://pan.dev/scm/api/)

### Cloud NGFW API
REST APIs for managing Palo Alto Networks Cloud NGFW, a cloud-native managed firewall service available on AWS and Azure. The API supports creating and managing firewall resources, configuring security rules and rule stacks, managing FQDN lists and prefix lists, and retrieving firewall logs. On AWS, authentication uses IAM roles; on Azure, authentication uses Azure Active Directory. Cloud NGFW delivers next-generation firewall capabilities as a fully managed cloud service without requiring infrastructure management.

**Human URL:** [https://pan.dev/cloudngfw/aws/api/](https://pan.dev/cloudngfw/aws/api/)


#### Tags:

 - Cloud-Native Firewall, AWS, Azure, Cloud Security, Managed Service

#### Properties

- [Documentation](https://pan.dev/cloudngfw/aws/api/)
- [Documentation](https://pan.dev/cloudngfw/docs/getstarted_azure/)

### WildFire API
A cloud-based API for submitting files, URLs, and links for advanced malware analysis in the WildFire sandbox environment. The API returns threat verdicts (benign, malware, grayware, phishing) and detailed analysis reports including behavioral indicators, network activity, and file artifacts. Supports file submission via multipart form upload, verdict queries by hash (MD5, SHA-256), and retrieval of PCAP files and detailed analysis reports. WildFire processes over 10 million unique samples daily across the global threat intelligence network.

**Human URL:** [https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api)


#### Tags:

 - Malware Analysis, Sandbox, File Analysis, Threat Prevention, Verdicts

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api)
- [GettingStarted](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api/get-started-with-the-wildfire-api)
- [OpenAPI](openapi/palo-alto-wildfire-api-openapi-original.yml)

### Threat Vault API
A REST API for querying Palo Alto Networks threat signature metadata, content release notes, and threat intelligence data. The API provides access to antivirus signatures, anti-spyware signatures, vulnerability protection (IPS) signatures, and file type identification data. Supports queries by signature ID, CVE, threat name, and content release version. Replaces the deprecated AutoFocus API for threat intelligence lookups. Requires an Advanced Threat Prevention or Threat Prevention subscription. Authentication uses an API key in the X-API-KEY header.

**Human URL:** [https://pan.dev/threat-vault/api/](https://pan.dev/threat-vault/api/)


#### Tags:

 - Threat Intelligence, Signatures, IPS, Antivirus, CVE

#### Properties

- [Documentation](https://pan.dev/threat-vault/api/)
- [GettingStarted](https://pan.dev/cdss/docs/getstarted/)
- [OpenAPI](openapi/palo-alto-threat-vault-api-openapi-original.yml)

### AutoFocus API (Deprecated)
A threat intelligence API that provided contextual information about malware, campaigns, and threat actors observed across the Palo Alto Networks global threat intelligence network. AutoFocus reached end-of-sale on September 30, 2022, and end-of-support on September 30, 2025. Developers should migrate to the Threat Vault API for threat signature lookups and to Cortex XDR or XSIAM for advanced threat intelligence and investigation capabilities.

**Human URL:** [https://docs.paloaltonetworks.com/autofocus/autofocus-api](https://docs.paloaltonetworks.com/autofocus/autofocus-api)


#### Tags:

 - Threat Intelligence, Malware, Analysis, Deprecated

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/autofocus/autofocus-api)
- [GettingStarted](https://docs.paloaltonetworks.com/autofocus/autofocus-api/get-started-with-the-autofocus-api)

### IoT Security API
A REST API for managing IoT and OT device security including device discovery, profiling, vulnerability assessment, and security policy recommendations. The API provides endpoints for retrieving discovered device inventories, security alerts, vulnerability details, and recommended network segmentation policies. Authentication uses X-Key-Id and X-Access-Key headers with keys generated from the IoT Security portal. Rate limited to 60 requests per minute.

**Human URL:** [https://pan.dev/iot/api/](https://pan.dev/iot/api/)


#### Tags:

 - IoT, Device Security, OT Security, Network Segmentation, Asset Discovery

#### Properties

- [Documentation](https://pan.dev/iot/api/)

### Data Loss Prevention API
A REST API for managing enterprise data loss prevention across Palo Alto Networks platforms. The API provides access to DLP incidents, policy violation reports, data pattern matches, and remediation workflows. Supports reviewing and managing incidents detected across network traffic, cloud applications, and email channels. Uses SASE OAuth 2.0 authentication aligned with the broader Prisma SASE authentication framework.

**Human URL:** [https://pan.dev/dlp/api/](https://pan.dev/dlp/api/)


#### Tags:

 - DLP, Data Security, Compliance, Incident Management, Data Classification

#### Properties

- [Documentation](https://pan.dev/dlp/api/)

### Prisma Access API
REST APIs for configuring and monitoring Prisma Access, Palo Alto Networks' cloud-delivered SASE platform. The Configuration API manages security policies, remote networks, service connections, and mobile user configurations for cloud-managed tenants. The Insights API (versions 1.0 through 3.0) provides health monitoring, tunnel status, bandwidth utilization, and user connectivity data. Authentication uses OAuth 2.0 with tenant service group (TSG) based credentials via the common SASE authentication framework.

**Human URL:** [https://pan.dev/access/api/prisma-access-config/](https://pan.dev/access/api/prisma-access-config/)


#### Tags:

 - SASE, Zero Trust, Remote Access, Cloud Security, Configuration

#### Properties

- [Documentation](https://pan.dev/access/api/prisma-access-config/)
- [APIReference](https://pan.dev/access/api/insights/)
- [GettingStarted](https://pan.dev/sase/docs/)

### Autonomous DEM API
A REST API for monitoring digital experience metrics within Prisma Access environments. The Autonomous Digital Experience Management (ADEM) API provides application performance data, network path analysis, endpoint health metrics, and user experience scoring. Supports querying performance data by user, application, location, and time range to identify connectivity and performance issues affecting remote and branch users connected through Prisma Access.

**Human URL:** [https://pan.dev/access/api/adem/autonomous-dem-api/](https://pan.dev/access/api/adem/autonomous-dem-api/)


#### Tags:

 - Digital Experience, Monitoring, Performance, SASE, Network Analytics

#### Properties

- [Documentation](https://pan.dev/access/api/adem/autonomous-dem-api/)
- [GettingStarted](https://pan.dev/access/docs/adem/getstarted/)

### Prisma SD-WAN API
REST APIs for managing Prisma SD-WAN (formerly CloudGenix) branch networking infrastructure. The API supports configuration of sites, WAN interfaces, routing policies, application definitions, path quality monitoring, and network analytics. Provides both a unified API using SASE OAuth 2.0 authentication and a legacy API with session token authentication. Supports full lifecycle management of SD-WAN deployments including site provisioning, policy configuration, and real-time network telemetry retrieval.

**Human URL:** [https://pan.dev/sdwan/docs/](https://pan.dev/sdwan/docs/)


#### Tags:

 - SD-WAN, Branch Networking, WAN Optimization, CloudGenix, Routing

#### Properties

- [Documentation](https://pan.dev/sdwan/docs/)
- [APIReference](https://pan.dev/sdwan/api/)

### Prisma Cloud CSPM API
The Cloud Security Posture Management API for Prisma Cloud (formerly RedLock) providing programmatic access to cloud security monitoring across AWS, Azure, GCP, and Oracle Cloud. The API supports managing security alerts, compliance policies, cloud accounts, asset inventories, and remediation workflows. Endpoints cover alert management, policy configuration, compliance reporting, cloud account onboarding, resource queries using RQL (Resource Query Language), and integration management. Authentication uses JWT tokens obtained from the /login endpoint with access key credentials.

**Human URL:** [https://pan.dev/prisma-cloud/api/cspm/](https://pan.dev/prisma-cloud/api/cspm/)


#### Tags:

 - Cloud Security, CSPM, Compliance, Cloud Posture, Multi-Cloud

#### Properties

- [Documentation](https://pan.dev/prisma-cloud/api/cspm/)
- [Authentication](https://prisma.pan.dev/api/cloud/api-auth/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-cspm-api-openapi-original.yml)
- [AsyncAPI](asyncapi/palo-alto-prisma-cloud-webhooks-asyncapi-original.yml)

### Prisma Cloud Compute API
The Cloud Workload Protection Platform (CWPP) API for Prisma Cloud (formerly Twistlock) providing security for containers, hosts, and serverless functions. The API covers image vulnerability scanning, runtime defense policies, compliance checks, registry scanning, CI/CD pipeline integration, and defender deployment management. Supports both SaaS and self-hosted Console deployments. Authentication uses time-limited tokens (30-minute validity) obtained from the /api/v1/authenticate endpoint or HTTP Basic authentication.

**Human URL:** [https://pan.dev/compute/api/](https://pan.dev/compute/api/)


#### Tags:

 - Container Security, CWPP, Kubernetes, Serverless, Runtime Protection

#### Properties

- [Documentation](https://pan.dev/compute/api/)
- [Authentication](https://pan.dev/compute/api/access-api-self-hosted/)

### Prisma Cloud Code Security API
A REST API for Prisma Cloud Application Security (formerly Bridgecrew) providing infrastructure-as-code scanning, software composition analysis, and supply chain security. The API supports checking Terraform, CloudFormation, Kubernetes manifests, and Dockerfiles against security policies, managing code repositories, retrieving scan results, and configuring fix suggestions. Integrates with CI/CD pipelines for shift-left security enforcement during the development lifecycle.

**Human URL:** [https://pan.dev/prisma-cloud/api/code/](https://pan.dev/prisma-cloud/api/code/)


#### Tags:

 - Code Security, IaC Scanning, Supply Chain, DevSecOps, Shift Left

#### Properties

- [Documentation](https://pan.dev/prisma-cloud/api/code/)

### Cortex XDR API
A REST API for the Cortex XDR extended detection and response platform providing programmatic access to incident management, alert handling, endpoint operations, and threat hunting. Key API modules include incidents (get, update, close), alerts (get details, exclusions), endpoints (isolate, unisolate, scan, get agent info), scripts (execute, get results), and audit logs. Authentication uses API key pairs (API Key ID + API Key) with support for Standard, Advanced, and RBAC key types providing different permission levels.

**Human URL:** [https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API)


#### Tags:

 - XDR, Detection, Response, Incidents, Endpoint Security

#### Properties

- [Documentation](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API)
- [GettingStarted](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API/Get-Started-with-APIs)
- [OpenAPI](openapi/palo-alto-cortex-xdr-api-openapi-original.yml)

### Cortex XSOAR API
APIs and development framework for Cortex XSOAR (formerly Demisto), the security orchestration, automation, and response platform. The REST API provides programmatic access to incidents, investigations, war rooms, playbooks, and integration instances. The integration development framework enables building custom integrations for the XSOAR marketplace with 750+ verified integrations. Supports Python and PowerShell integration development with the demisto-sdk CLI tool. The XSOAR Developer Hub provides comprehensive documentation for building integrations, playbooks, and automation scripts.

**Human URL:** [https://xsoar.pan.dev/](https://xsoar.pan.dev/)


#### Tags:

 - SOAR, Automation, Playbooks, Integrations, Incident Response

#### Properties

- [Documentation](https://xsoar.pan.dev/)
- [APIReference](https://xsoar.pan.dev/docs/reference/api/demisto-class)
- [Documentation](https://cortex.marketplace.pan.dev/marketplace/)
- [GitHubRepository](https://github.com/demisto/content)
- [JSONSchema](json-schema/cortex-xsoar-integration-manifest-schema.json)

### Cortex XSIAM API
A REST API for Cortex XSIAM, the AI-driven security operations platform that combines SIEM, XDR, SOAR, and ASM capabilities. The API provides endpoints for incident management, alert handling, data ingestion configuration, XQL query execution, asset management, and automation rule management. Shares endpoint patterns with Cortex XDR but includes additional capabilities for log collection configuration, data model management, and AI-assisted investigation. Authentication uses Standard or Advanced API key pairs.

**Human URL:** [https://docs-cortex.paloaltonetworks.com/r/Cortex-XSIAM-REST-API](https://docs-cortex.paloaltonetworks.com/r/Cortex-XSIAM-REST-API)


#### Tags:

 - AI-Driven SOC, SIEM, XDR, Automation, Security Analytics

#### Properties

- [Documentation](https://docs-cortex.paloaltonetworks.com/r/Cortex-XSIAM-REST-API)

### Prisma AIRS API
The AI Runtime Security API for securing generative AI applications against prompt injection, data leakage, toxic content, and other AI-specific threats. The API scans prompts and model responses in real time, providing threat detection and content classification for LLM-powered applications. Supports integration via REST API or the pan-aisecurity Python SDK. Part of Prisma AIRS, which provides comprehensive AI security across discovery, posture management, and runtime protection for enterprise AI deployments.

**Human URL:** [https://pan.dev/airs/](https://pan.dev/airs/)


#### Tags:

 - AI Security, LLM Security, Prompt Injection, AI Runtime, GenAI

#### Properties

- [Documentation](https://pan.dev/airs/)
- [APIReference](https://pan.dev/prisma-airs/api/airuntimesecurity/airuntimesecurityapi/)
- [GitHubRepository](https://github.com/PaloAltoNetworks/aisecurity-python-sdk)

### Security Advisory API
A REST API (currently in beta) for programmatically querying Palo Alto Networks security advisories published by the Product Security Incident Response Team (PSIRT). The API supports filtering advisories by CVE ID, severity, product, and date range. Returns advisory details including vulnerability descriptions, affected versions, CVSS scores, and remediation guidance. Also available as an RSS feed for continuous monitoring of new security advisories.

**Human URL:** [https://security.paloaltonetworks.com/api](https://security.paloaltonetworks.com/api)


#### Tags:

 - Security Advisories, CVE, Vulnerabilities, PSIRT, Patching

#### Properties

- [Documentation](https://security.paloaltonetworks.com/api)
- [Feed](https://security.paloaltonetworks.com/rss.xml)

## Common Properties

- [Portal](https://pan.dev/)
- [Documentation](https://docs.paloaltonetworks.com/)
- [Documentation](https://docs.paloaltonetworks.com/develop/api)
- [Website](https://www.paloaltonetworks.com)
- [Support](https://www.paloaltonetworks.com/services/support)
- [Blog](https://www.paloaltonetworks.com/blog/)
- [Status](https://status.paloaltonetworks.com/)
- [Forum](https://live.paloaltonetworks.com/)
- [Security](https://security.paloaltonetworks.com/)
- [GitHubOrganization](https://github.com/PaloAltoNetworks)
- [GitHubOrganization](https://github.com/demisto)
- [GitHubOrganization](https://github.com/pan-unit42)
- [GitHubRepository](https://github.com/PaloAltoNetworks/pan-os-python)
- [GitHubRepository](https://github.com/PaloAltoNetworks/pango)
- [TerraformProvider](https://registry.terraform.io/namespaces/PaloAltoNetworks)
- [AnsibleCollection](https://galaxy.ansible.com/paloaltonetworks/panos)
- [Training](https://www.paloaltonetworks.com/services/education)
- [Training](https://learn.paloaltonetworks.com)
- [PrivacyPolicy](https://www.paloaltonetworks.com/legal/privacy)
- [TermsOfService](https://www.paloaltonetworks.com/legal)
- [X](https://x.com/PaloAltoNtwks)
- [YouTube](https://www.youtube.com/@pabornetworks)
- [Partner](https://www.paloaltonetworks.com/partners)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
