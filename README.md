# Palo Alto Networks (palo-alto-networks)
Palo Alto Networks is a global cybersecurity leader providing advanced security platforms and services across network security, cloud security, and security operations. Its developer platform at pan.dev offers REST and XML APIs for PAN-OS firewalls, Strata Cloud Manager, Prisma Cloud (CSPM, CWPP, code security), Prisma Access and SD-WAN for SASE, Cortex XDR/XSOAR/XSIAM for security operations, and cloud-delivered security services including WildFire, Threat Vault, IoT Security, and DLP.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud Security, Cybersecurity, Firewall, Network Security, SASE, SOAR, Threat Intelligence, XDR

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-17

## APIs

### PAN-OS REST API
A RESTful API for managing PAN-OS next-generation firewalls including security policies, network objects, address groups, and device configuration. The REST API provides simplified JSON-based access to common firewall operations as an alternative to the XML API. Supports CRUD operations on policy rules, address objects, service objects, and security profiles. Authentication uses API keys generated from the firewall management interface or via the XML API keygen command.

**Human URL:** [https://pan.dev/panos/docs/restapi/](https://pan.dev/panos/docs/restapi/)

#### Tags:

 - Configuration, Firewall, Network Security, Policies, REST API

#### Properties

- [Documentation](https://pan.dev/panos/docs/restapi/)
- [GettingStarted](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-rest-api)
- [APIReference](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/pan-os-rest-api-reference)
- [Authentication](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-rest-api/get-your-api-key)
- [OpenAPI](openapi/palo-alto-pan-os-rest-api-openapi-original.yml)

### PAN-OS XML API
The comprehensive XML-based API for PAN-OS providing full access to all firewall configuration, operational commands, reporting, logging, and commit operations. Supports request types including keygen for authentication, config for configuration changes using XPath, op for operational commands, report for generating reports, log for retrieving traffic and threat logs, and user-id for dynamic user-to-IP mapping.

**Human URL:** [https://pan.dev/panos/docs/xmlapi/](https://pan.dev/panos/docs/xmlapi/)

#### Tags:

 - Configuration, Firewall, Monitoring, Operations, XML

#### Properties

- [Documentation](https://pan.dev/panos/docs/xmlapi/)
- [GettingStarted](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-xml-api)
- [APIReference](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/pan-os-xml-api-request-types)
- [Authentication](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-xml-api/get-your-api-key)

### PAN-OS OpenConfig API
Management interface for PAN-OS based on OpenConfig standard data models, providing gNMI and gNOI services through the OpenConfig plugin. Supports network automation for BGP, interfaces, LACP, LLDP, VLANs, local routes, system, and platform configuration, as well as telemetry streaming. Includes a PAN-OS OpenConfig XML API for integration with standard network management tools.

**Human URL:** [https://docs.paloaltonetworks.com/openconfig](https://docs.paloaltonetworks.com/openconfig)

#### Tags:

 - Firewall, gNMI, Network Automation, OpenConfig, Telemetry

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/openconfig)
- [GettingStarted](https://docs.paloaltonetworks.com/openconfig/2-0/openconfig-admin/getting-started)
- [APIReference](https://docs.paloaltonetworks.com/openconfig/2-0/openconfig-admin/pan-os-models/pan-os-openconfig-xmlapi)

### Panorama API
The Panorama API uses the same PAN-OS XML and REST API interfaces but provides centralized management of multiple firewalls from a single management server. Supports device group and template stack operations for pushing configuration to managed firewalls, centralized logging and reporting, and multi-device commit workflows. Panorama-specific API operations include managing device groups, template stacks, log collectors, and performing push operations to managed devices.

**Human URL:** [https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api)

#### Tags:

 - Centralized Management, Device Groups, Firewall, Orchestration, Templates

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api)
- [APIReference](https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api)

### Strata Cloud Manager API
A unified cloud-based API for managing Palo Alto Networks next-generation firewalls and SASE from a single management plane. Strata Cloud Manager provides configuration management for security policies, network objects, and device settings across hardware, virtual, and cloud-native firewalls. The API uses OAuth 2.0 authentication with bearer tokens and provides RESTful endpoints for policy lifecycle management, object CRUD operations, and deployment workflows.

**Human URL:** [https://pan.dev/scm/docs/home/](https://pan.dev/scm/docs/home/)

#### Tags:

 - Cloud Management, Configuration, NGFW, SASE, Unified Management

#### Properties

- [Documentation](https://pan.dev/scm/docs/home/)
- [APIReference](https://pan.dev/scm/api/)
- [GettingStarted](https://pan.dev/scm/docs/getstarted/)
- [BestPractices](https://pan.dev/scm/docs/api-best-practices/)
- [ChangeLog](https://pan.dev/scm/docs/release-notes/)
- [OpenAPI](openapi/palo-alto-strata-cloud-manager-api-openapi-original.yml)
- [Go SDK](https://github.com/PaloAltoNetworks/scm-go)

### Cloud NGFW API
REST APIs for managing Palo Alto Networks Cloud NGFW, a cloud-native managed firewall service available on AWS and Azure. The API supports creating and managing firewall resources, configuring security rules and rule stacks, managing FQDN lists and prefix lists, and retrieving firewall logs. On AWS, authentication uses IAM roles; on Azure, authentication uses Azure Active Directory.

**Human URL:** [https://pan.dev/cloudngfw/aws/api/](https://pan.dev/cloudngfw/aws/api/)

#### Tags:

 - AWS, Azure, Cloud Security, Cloud-Native Firewall, Managed Service

#### Properties

- [Documentation](https://pan.dev/cloudngfw/aws/api/)
- [GettingStarted](https://pan.dev/cloudngfw/docs/getstarted_azure/)
- [OpenAPI](openapi/palo-alto-cloud-ngfw-api-openapi-original.yml)

### WildFire API
A cloud-based API for submitting files, URLs, and links for advanced malware analysis in the WildFire sandbox environment. The API returns threat verdicts (benign, malware, grayware, phishing) and detailed analysis reports including behavioral indicators, network activity, and file artifacts. Supports file submission via multipart form upload, verdict queries by hash (MD5, SHA-256), and retrieval of PCAP files and detailed analysis reports.

**Human URL:** [https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api)

#### Tags:

 - File Analysis, Malware Analysis, Sandbox, Threat Prevention, Verdicts

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api)
- [GettingStarted](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api/get-started-with-the-wildfire-api)
- [APIReference](https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api)
- [OpenAPI](openapi/palo-alto-wildfire-api-openapi-original.yml)

### Threat Vault API
A REST API for querying Palo Alto Networks threat signature metadata, content release notes, and threat intelligence data. The API provides access to antivirus signatures, anti-spyware signatures, vulnerability protection (IPS) signatures, and file type identification data. Supports queries by signature ID, CVE, threat name, and content release version. Replaces the deprecated AutoFocus API for threat intelligence lookups. Requires an Advanced Threat Prevention or Threat Prevention subscription.

**Human URL:** [https://pan.dev/threat-vault/api/](https://pan.dev/threat-vault/api/)

#### Tags:

 - Antivirus, CVE, IPS, Signatures, Threat Intelligence

#### Properties

- [Documentation](https://pan.dev/threat-vault/api/)
- [GettingStarted](https://pan.dev/cdss/docs/getstarted/)
- [Authentication](https://pan.dev/cdss/docs/authentication/)
- [OpenAPI](openapi/palo-alto-threat-vault-api-openapi-original.yml)

### AutoFocus API (Deprecated)
A threat intelligence API that provided contextual information about malware, campaigns, and threat actors observed across the Palo Alto Networks global threat intelligence network. AutoFocus reached end-of-sale on September 30, 2022, and end-of-support on September 30, 2025. Developers should migrate to the Threat Vault API for threat signature lookups and to Cortex XDR or XSIAM for advanced threat intelligence and investigation capabilities.

**Human URL:** [https://docs.paloaltonetworks.com/autofocus/autofocus-api](https://docs.paloaltonetworks.com/autofocus/autofocus-api)

#### Tags:

 - Analysis, Deprecated, Malware, Threat Intelligence

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/autofocus/autofocus-api)
- [GettingStarted](https://docs.paloaltonetworks.com/autofocus/autofocus-api/get-started-with-the-autofocus-api)

### IoT Security API
A REST API for managing IoT and OT device security including device discovery, profiling, vulnerability assessment, and security policy recommendations. The API provides endpoints for retrieving discovered device inventories, security alerts, vulnerability details, and recommended network segmentation policies. Authentication uses X-Key-Id and X-Access-Key headers with keys generated from the IoT Security portal. Rate limited to 60 requests per minute.

**Human URL:** [https://pan.dev/iot/api/](https://pan.dev/iot/api/)

#### Tags:

 - Asset Discovery, Device Security, IoT, Network Segmentation, OT Security

#### Properties

- [Documentation](https://pan.dev/iot/api/)
- [OpenAPI](openapi/palo-alto-iot-security-api-openapi-original.yml)

### Data Loss Prevention API
A REST API for managing enterprise data loss prevention across Palo Alto Networks platforms. The API provides access to DLP incidents, policy violation reports, data pattern matches, and remediation workflows. Supports reviewing and managing incidents detected across network traffic, cloud applications, and email channels. Uses SASE OAuth 2.0 authentication aligned with the broader Prisma SASE authentication framework.

**Human URL:** [https://pan.dev/dlp/api/](https://pan.dev/dlp/api/)

#### Tags:

 - Compliance, Data Classification, Data Security, DLP, Incident Management

#### Properties

- [Documentation](https://pan.dev/dlp/api/)
- [OpenAPI](openapi/palo-alto-dlp-api-openapi-original.yml)

### Prisma Access API
REST APIs for configuring and monitoring Prisma Access, Palo Alto Networks' cloud-delivered SASE platform. The Configuration API manages security policies, remote networks, service connections, and mobile user configurations for cloud-managed tenants. The Insights API (versions 1.0 through 3.0) provides health monitoring, tunnel status, bandwidth utilization, and user connectivity data.

**Human URL:** [https://pan.dev/access/api/prisma-access-config/](https://pan.dev/access/api/prisma-access-config/)

#### Tags:

 - Cloud Security, Configuration, Remote Access, SASE, Zero Trust

#### Properties

- [Documentation](https://pan.dev/access/api/prisma-access-config/)
- [APIReference](https://pan.dev/access/api/insights/)
- [GettingStarted](https://pan.dev/sase/docs/)
- [ChangeLog](https://pan.dev/sase/docs/release-notes/changelog/)
- [OpenAPI](openapi/palo-alto-prisma-access-api-openapi-original.yml)

### Autonomous DEM API
A REST API for monitoring digital experience metrics within Prisma Access environments. The Autonomous Digital Experience Management (ADEM) API provides application performance data, network path analysis, endpoint health metrics, and user experience scoring. Supports querying performance data by user, application, location, and time range to identify connectivity and performance issues affecting remote and branch users connected through Prisma Access.

**Human URL:** [https://pan.dev/access/api/adem/autonomous-dem-api/](https://pan.dev/access/api/adem/autonomous-dem-api/)

#### Tags:

 - Digital Experience, Monitoring, Network Analytics, Performance, SASE

#### Properties

- [Documentation](https://pan.dev/access/api/adem/autonomous-dem-api/)
- [GettingStarted](https://pan.dev/access/docs/adem/getstarted/)
- [OpenAPI](openapi/palo-alto-autonomous-dem-api-openapi-original.yml)

### Prisma SD-WAN API
REST APIs for managing Prisma SD-WAN (formerly CloudGenix) branch networking infrastructure. The API supports configuration of sites, WAN interfaces, routing policies, application definitions, path quality monitoring, and network analytics. Provides both a unified API using SASE OAuth 2.0 authentication and a legacy API with session token authentication.

**Human URL:** [https://pan.dev/sdwan/docs/](https://pan.dev/sdwan/docs/)

#### Tags:

 - Branch Networking, CloudGenix, Routing, SD-WAN, WAN Optimization

#### Properties

- [Documentation](https://pan.dev/sdwan/docs/)
- [APIReference](https://pan.dev/sdwan/api/)
- [OpenAPI](openapi/palo-alto-prisma-sd-wan-api-openapi-original.yml)

### Prisma Cloud CSPM API
The Cloud Security Posture Management API for Prisma Cloud (formerly RedLock) providing programmatic access to cloud security monitoring across AWS, Azure, GCP, and Oracle Cloud. The API supports managing security alerts, compliance policies, cloud accounts, asset inventories, and remediation workflows. Endpoints cover alert management, policy configuration, compliance reporting, cloud account onboarding, resource queries using RQL (Resource Query Language), and integration management.

**Human URL:** [https://pan.dev/prisma-cloud/api/cspm/](https://pan.dev/prisma-cloud/api/cspm/)

#### Tags:

 - Cloud Posture, Cloud Security, Compliance, CSPM, Multi-Cloud

#### Properties

- [Documentation](https://pan.dev/prisma-cloud/api/cspm/)
- [Authentication](https://prisma.pan.dev/api/cloud/api-auth/)
- [GettingStarted](https://pan.dev/prisma-cloud/docs/cspm/cspm-gs/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-cspm-api-openapi-original.yml)
- [AsyncAPI](asyncapi/palo-alto-prisma-cloud-webhooks-asyncapi-original.yml)

### Prisma Cloud Compute API
The Cloud Workload Protection Platform (CWPP) API for Prisma Cloud (formerly Twistlock) providing security for containers, hosts, and serverless functions. The API covers image vulnerability scanning, runtime defense policies, compliance checks, registry scanning, CI/CD pipeline integration, and defender deployment management. Supports both SaaS and self-hosted Console deployments.

**Human URL:** [https://pan.dev/compute/api/](https://pan.dev/compute/api/)

#### Tags:

 - Container Security, CWPP, Kubernetes, Runtime Protection, Serverless

#### Properties

- [Documentation](https://pan.dev/compute/api/)
- [Authentication](https://pan.dev/compute/api/access-api-self-hosted/)
- [APIReference](https://pan.dev/compute/api/stable-endpoints/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-compute-api-openapi-original.yml)

### Prisma Cloud Code Security API
A REST API for Prisma Cloud Application Security (formerly Bridgecrew) providing infrastructure-as-code scanning, software composition analysis, and supply chain security. The API supports checking Terraform, CloudFormation, Kubernetes manifests, and Dockerfiles against security policies, managing code repositories, retrieving scan results, and configuring fix suggestions. Integrates with CI/CD pipelines for shift-left security enforcement during the development lifecycle.

**Human URL:** [https://pan.dev/prisma-cloud/api/code/](https://pan.dev/prisma-cloud/api/code/)

#### Tags:

 - Code Security, DevSecOps, IaC Scanning, Shift Left, Supply Chain

#### Properties

- [Documentation](https://pan.dev/prisma-cloud/api/code/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-code-security-api-openapi-original.yml)

### Cortex XDR API
A REST API for the Cortex XDR extended detection and response platform providing programmatic access to incident management, alert handling, endpoint operations, and threat hunting. Key API modules include incidents (get, update, close), alerts (get details, exclusions), endpoints (isolate, unisolate, scan, get agent info), scripts (execute, get results), and audit logs.

**Human URL:** [https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API)

#### Tags:

 - Detection, Endpoint Security, Incidents, Response, XDR

#### Properties

- [Documentation](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API)
- [GettingStarted](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API/Get-Started-with-APIs)
- [APIReference](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API/API-Reference)
- [OpenAPI](openapi/palo-alto-cortex-xdr-api-openapi-original.yml)
- [AsyncAPI](asyncapi/palo-alto-cortex-xdr-webhooks-asyncapi-original.yml)

### Cortex XSOAR API
APIs and development framework for Cortex XSOAR (formerly Demisto), the security orchestration, automation, and response platform. The REST API provides programmatic access to incidents, investigations, war rooms, playbooks, and integration instances. The integration development framework enables building custom integrations for the XSOAR marketplace with 750+ verified integrations. Supports Python and PowerShell integration development with the demisto-sdk CLI tool.

**Human URL:** [https://xsoar.pan.dev/](https://xsoar.pan.dev/)

#### Tags:

 - Automation, Incident Response, Integrations, Playbooks, SOAR

#### Properties

- [Documentation](https://xsoar.pan.dev/)
- [APIReference](https://xsoar.pan.dev/docs/reference/api/demisto-class)
- [GettingStarted](https://xsoar.pan.dev/docs/concepts/getting-started-guide)
- [Marketplace](https://cortex.marketplace.pan.dev/marketplace/)
- [GitHubRepository](https://github.com/demisto/content)
- [OpenAPI](openapi/palo-alto-cortex-xsoar-api-openapi-original.yml)

### Cortex XSIAM API
A REST API for Cortex XSIAM, the AI-driven security operations platform that combines SIEM, XDR, SOAR, and ASM capabilities. The API provides endpoints for incident management, alert handling, data ingestion configuration, XQL query execution, asset management, and automation rule management. Shares endpoint patterns with Cortex XDR but includes additional capabilities for log collection configuration, data model management, and AI-assisted investigation.

**Human URL:** [https://docs-cortex.paloaltonetworks.com/r/Cortex-XSIAM-REST-API](https://docs-cortex.paloaltonetworks.com/r/Cortex-XSIAM-REST-API)

#### Tags:

 - AI-Driven SOC, Automation, Security Analytics, SIEM, XDR

#### Properties

- [Documentation](https://docs-cortex.paloaltonetworks.com/r/Cortex-XSIAM-REST-API)
- [GettingStarted](https://docs-cortex.paloaltonetworks.com/r/Cortex-XDR-REST-API/Get-Started-with-APIs)
- [OpenAPI](openapi/palo-alto-cortex-xsiam-api-openapi-original.yml)
- [AsyncAPI](asyncapi/palo-alto-cortex-xsiam-data-ingestion-asyncapi-original.yml)

### Prisma AIRS AI Runtime Security API
The AI Runtime Security API (API Intercept) for securing generative AI applications, AI models, AI data, and AI agents against prompt injection, data leakage, toxic content, malicious URLs, database security attacks, malicious code, and other AI-specific threats. Provides Scan APIs for real-time threat detection on prompts and model responses, and Management APIs for configuring security profiles, API keys, and deployments. Supports Secure MCP, custom topic guardrails, contextual grounding, and data masking. Available in US, EU (Germany), India, and Singapore regions. Integrates via REST API or the pan-aisecurity Python SDK with API key or OAuth 2.0 authentication.

**Human URL:** [https://pan.dev/airs/](https://pan.dev/airs/)

#### Tags:

 - AI Runtime, AI Security, API Intercept, GenAI, LLM Security, MCP Security, Prompt Injection

#### Properties

- [Documentation](https://pan.dev/airs/)
- [APIReference](https://pan.dev/prisma-airs/api/airuntimesecurity/airuntimesecurityapi/)
- [GettingStarted](https://docs.paloaltonetworks.com/ai-runtime-security/activation-and-onboarding/ai-runtime-security-api-intercept-overview)
- [Python SDK](https://pan.dev/prisma-airs/api/airuntimesecurity/pythonsdk/)
- [GitHubRepository](https://github.com/PaloAltoNetworks/aisecurity-python-sdk)
- [AIRS Management Python SDK](https://github.com/PaloAltoNetworks/airs-api-mgmt-sdk)
- [OpenAPI](openapi/palo-alto-prisma-airs-api-openapi-original.yml)

### Security Advisory API
A REST API (currently in beta) for programmatically querying Palo Alto Networks security advisories published by the Product Security Incident Response Team (PSIRT). The API supports filtering advisories by CVE ID, severity, product, and date range. Returns advisory details including vulnerability descriptions, affected versions, CVSS scores, and remediation guidance. Also available as an RSS feed for continuous monitoring of new security advisories.

**Human URL:** [https://security.paloaltonetworks.com/api](https://security.paloaltonetworks.com/api)

#### Tags:

 - CVE, Patching, PSIRT, Security Advisories, Vulnerabilities

#### Properties

- [Documentation](https://security.paloaltonetworks.com/api)
- [Feed](https://security.paloaltonetworks.com/rss.xml)
- [OpenAPI](openapi/palo-alto-security-advisory-api-openapi-original.yml)

### Cortex Xpanse API
A REST API for Cortex Xpanse, the attack surface management platform that discovers, evaluates, and mitigates risks on internet-facing assets. The API provides programmatic access to asset inventories, attack surface rules, risk identification, and remediation workflows. Supports querying discovered services, certificates, domains, and cloud resources exposed to the internet. Authentication uses RBAC API key pairs consistent with other Cortex platform APIs.

**Human URL:** [https://docs-cortex.paloaltonetworks.com/r/Cortex-Xpanse-REST-API](https://docs-cortex.paloaltonetworks.com/r/Cortex-Xpanse-REST-API)

#### Tags:

 - Asset Discovery, Attack Surface Management, Exposure Management, Internet-Facing Assets, Risk Assessment

#### Properties

- [Documentation](https://docs-cortex.paloaltonetworks.com/r/Cortex-Xpanse-REST-API)
- [OpenAPI](openapi/palo-alto-cortex-xpanse-api-openapi-original.yml)

### DNS Security API
A REST API (currently in beta) for retrieving DNS domain details, categorization information, and contextual network access statistics from the Palo Alto Networks DNS Security service. Supports querying domain reputation, categorization data, and related threat intelligence. Requires a DNS Security subscription and uses API key authentication via the X-DNS-API-APIKEY header.

**Human URL:** [https://pan.dev/dns-security/api/](https://pan.dev/dns-security/api/)

#### Tags:

 - Beta, DNS, Domain Categorization, Domain Security, Threat Intelligence

#### Properties

- [Documentation](https://pan.dev/dns-security/api/)
- [GettingStarted](https://pan.dev/cdss/docs/getstarted/)
- [Authentication](https://pan.dev/cdss/docs/authentication/)
- [OpenAPI](openapi/palo-alto-dns-security-api-openapi-original.yml)

### Email DLP API
A REST API for programmatically reviewing and managing Email DLP incidents detected across enterprise email channels. The API supports retrieving incident details, updating verdicts on flagged emails, and managing remediation workflows for data loss prevention violations in email traffic. Uses region-specific endpoints and requires SOC_Admin, Superuser, or Data Security Administrator roles for access.

**Human URL:** [https://pan.dev/email-dlp/api/](https://pan.dev/email-dlp/api/)

#### Tags:

 - Compliance, Data Protection, DLP, Email Security, Incident Management

#### Properties

- [Documentation](https://pan.dev/email-dlp/api/)
- [OpenAPI](openapi/palo-alto-email-dlp-api-openapi-original.yml)

### SaaS Security API
A REST API for scanning and protecting assets stored in sanctioned SaaS applications. The API provides at-rest detection, inspection, and remediation capabilities for data stored across cloud applications including file scanning, policy violation detection, and automated remediation workflows. Supports integration with enterprise SaaS applications for continuous data security monitoring.

**Human URL:** [https://docs.paloaltonetworks.com/saas-security/saas-security-admin/saas-security-api](https://docs.paloaltonetworks.com/saas-security/saas-security-admin/saas-security-api)

#### Tags:

 - CASB, Cloud Applications, Compliance, Data Protection, SaaS Security

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/saas-security/saas-security-admin/saas-security-api)
- [OpenAPI](openapi/palo-alto-saas-security-api-openapi-original.yml)

### SaaS Security Posture Management API
A REST API for managing SaaS Security Posture Management providing continuous monitoring of misconfigured SaaS application settings. The API supports managing onboarded SaaS applications, retrieving configuration assessment details, accessing the application catalog, and managing JIRA integrations for remediation tracking. Part of the broader SASE platform with OAuth 2.0 authentication.

**Human URL:** [https://pan.dev/sase/api/sspm/](https://pan.dev/sase/api/sspm/)

#### Tags:

 - Compliance, Misconfiguration, SaaS Applications, SaaS Posture, SSPM

#### Properties

- [Documentation](https://pan.dev/sase/api/sspm/)
- [OpenAPI](openapi/palo-alto-sspm-api-openapi-original.yml)

### ZTNA Connector API
REST APIs for managing Zero Trust Network Access connectors within the Prisma Access SASE platform. The API supports creating and managing ZTNA connectors, applications, licenses, and connector groups for providing secure application access without traditional VPN infrastructure. Uses the common SASE OAuth 2.0 authentication framework with tenant service group credentials.

**Human URL:** [https://pan.dev/access/api/ztna/ztna-connector-apis/](https://pan.dev/access/api/ztna/ztna-connector-apis/)

#### Tags:

 - Connectors, Network Access, SASE, Zero Trust, ZTNA

#### Properties

- [Documentation](https://pan.dev/access/api/ztna/ztna-connector-apis/)
- [APIReference](https://pan.dev/access/api/ztna/ztna-connector-restful-api/)
- [OpenAPI](openapi/palo-alto-ztna-connector-api-openapi-original.yml)

### Prisma Access Browser API
REST APIs for scaling and automating processes related to the Prisma Access secure enterprise browser. The API supports browser deployment management, policy configuration, and user management for the cloud-delivered secure browser solution. Supports Super User (read/write) and View-Only Administrator roles for access control.

**Human URL:** [https://pan.dev/access/api/browser-mgmt/browser-mgmt-api/](https://pan.dev/access/api/browser-mgmt/browser-mgmt-api/)

#### Tags:

 - Browser Management, Enterprise Browser, SASE, Secure Browser, Web Security

#### Properties

- [Documentation](https://pan.dev/access/api/browser-mgmt/browser-mgmt-api/)
- [OpenAPI](openapi/palo-alto-prisma-access-browser-api-openapi-original.yml)

### SASE Tenancy Service API
A REST API for creating and managing Tenant Service Groups (TSGs) within the Palo Alto Networks SASE platform. The API supports building tenant hierarchies for multi-tenant deployments, managing TSG properties, and organizing service subscriptions across organizational units. Essential for managed security service providers and large enterprises with complex organizational structures. Uses OAuth 2.0 authentication.

**Human URL:** [https://pan.dev/sase/api/tenancy/](https://pan.dev/sase/api/tenancy/)

#### Tags:

 - Multi-Tenant, SASE, Service Provider, Tenant Management, TSG

#### Properties

- [Documentation](https://pan.dev/sase/api/tenancy/)
- [OpenAPI](openapi/palo-alto-sase-tenancy-api-openapi-original.yml)

### SASE IAM API
A REST API for managing identity and access on the SASE platform including creating service accounts, managing access policies, and configuring role-based access control for SASE API consumers. The API supports provisioning service account credentials used for OAuth 2.0 authentication across all SASE platform APIs. Part of the common SASE management services layer.

**Human URL:** [https://pan.dev/sase/api/iam/](https://pan.dev/sase/api/iam/)

#### Tags:

 - Access Control, Identity Management, RBAC, SASE, Service Accounts

#### Properties

- [Documentation](https://pan.dev/sase/api/iam/)
- [OpenAPI](openapi/palo-alto-sase-iam-api-openapi-original.yml)

### SASE Subscription Service API
A REST API for managing license subscriptions assigned to Tenant Service Groups within the SASE platform. The API supports querying subscription entitlements, managing license allocations across tenant hierarchies, and retrieving subscription status information. Uses OAuth 2.0 authentication consistent with other SASE platform APIs.

**Human URL:** [https://pan.dev/sase/api/subscription/](https://pan.dev/sase/api/subscription/)

#### Tags:

 - Entitlements, Licensing, SASE, Subscriptions, Tenant Management

#### Properties

- [Documentation](https://pan.dev/sase/api/subscription/)
- [OpenAPI](openapi/palo-alto-sase-subscription-api-openapi-original.yml)

### SASE Aggregate Monitoring API
A REST API for performing aggregated monitoring queries across SASE tenants. The API supports querying application usage, threat data, URL categorization, and license utilization across all tenants in a hierarchy. Provides multi-tenant visibility for managed security service providers and enterprise administrators overseeing multiple organizational units.

**Human URL:** [https://pan.dev/sase/api/mt-monitor/](https://pan.dev/sase/api/mt-monitor/)

#### Tags:

 - Analytics, Monitoring, Multi-Tenant, SASE, Threat Monitoring

#### Properties

- [Documentation](https://pan.dev/sase/api/mt-monitor/)
- [OpenAPI](openapi/palo-alto-sase-aggregate-monitoring-api-openapi-original.yml)

### AIOps for NGFW BPA API
A REST API for the AIOps Best Practice Assessment service that programmatically generates firewall configuration assessments against Palo Alto Networks best practice recommendations. The API supports generating BPA data, checking report status, and retrieving assessment reports in JSON format. Available for both free and premium AIOps for NGFW instances. Helps identify configuration gaps and security improvement opportunities.

**Human URL:** [https://pan.dev/aiops-ngfw-bpa/api/](https://pan.dev/aiops-ngfw-bpa/api/)

#### Tags:

 - AIOps, Assessment, Best Practices, Configuration Analysis, NGFW

#### Properties

- [Documentation](https://pan.dev/aiops-ngfw-bpa/api/)
- [OpenAPI](openapi/palo-alto-aiops-ngfw-bpa-api-openapi-original.yml)

### Strata Logging Service API
REST APIs for the Strata Logging Service (formerly Cortex Data Lake) providing log forwarding and query capabilities. The Log Forwarding API manages log forwarding profiles for syslog, HTTPS, and email destinations supporting CSV, LEEF, CEF, JSON, and PARQUET formats with up to 200 syslog destinations per instance. The Query Service API enables programmatic log retrieval and pagination across collected security telemetry data.

**Human URL:** [https://pan.dev/cdl/docs/log-forwarding/](https://pan.dev/cdl/docs/log-forwarding/)

#### Tags:

 - Analytics, Data Lake, Log Forwarding, Logging, SIEM Integration

#### Properties

- [Documentation](https://pan.dev/cdl/docs/log-forwarding/)
- [ChangeLog](https://pan.dev/cdl/docs/logforwarding/release-notes/relnotes/)
- [OpenAPI](openapi/palo-alto-strata-logging-service-api-openapi-original.yml)
- [AsyncAPI](asyncapi/palo-alto-strata-logging-forwarding-asyncapi-original.yml)

### Configuration Orchestration API
A REST API enabling third-party SD-WAN integration with Prisma Access Remote Networks. The API supports automated tunnel configuration, branch onboarding workflows, and coordination between third-party SD-WAN solutions and the Prisma Access SASE infrastructure. Designed for technology partners integrating their SD-WAN platforms with Palo Alto Networks SASE services.

**Human URL:** [https://pan.dev/sase/api/config-orch/configuration-orchestration-api/](https://pan.dev/sase/api/config-orch/configuration-orchestration-api/)

#### Tags:

 - Remote Networks, SASE, SD-WAN Integration, Third-Party, Tunnel Configuration

#### Properties

- [Documentation](https://pan.dev/sase/api/config-orch/configuration-orchestration-api/)
- [OpenAPI](openapi/palo-alto-sase-config-orchestration-api-openapi-original.yml)

### Prisma Cloud DSPM API
A REST API for Data Security Posture Management within Prisma Cloud providing visibility and control over sensitive data stored across multi-cloud environments. The API supports data discovery, classification, and risk assessment for cloud data stores including databases, object storage, and file systems. Authentication uses JWT tokens consistent with the broader Prisma Cloud API framework.

**Human URL:** [https://pan.dev/prisma-cloud/api/](https://pan.dev/prisma-cloud/api/)

#### Tags:

 - Classification, Cloud Data, Data Posture, Data Security, Multi-Cloud

#### Properties

- [Documentation](https://pan.dev/prisma-cloud/api/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-dspm-api-openapi-original.yml)

### SASE 5G Manage Services API
REST APIs for managing scalable, multi-tenant, agentless security for 5G networks. The API supports provisioning and configuring 5G security services that integrate with 5G authentication frameworks for securing mobile network traffic. Designed for telecommunications providers and enterprises deploying private 5G networks with Palo Alto Networks SASE security services.

**Human URL:** [https://pan.dev/sase/api/manage-services-5g/](https://pan.dev/sase/api/manage-services-5g/)

#### Tags:

 - 5G Security, Agentless Security, Mobile Network, Multi-Tenant, Telecommunications

#### Properties

- [Documentation](https://pan.dev/sase/api/manage-services-5g/)
- [OpenAPI](openapi/palo-alto-sase-5g-api-openapi-original.yml)

### Prisma AIRS AI Red Teaming API
An automated red teaming API for assessing the safety and security of generative AI systems including large language models and LLM-powered applications. The API simulates real-world threats by sending crafted attack prompts including jailbreaks, prompt injection, and input manipulation to target AI systems and evaluating responses. Supports creating scan targets, executing asynchronous vulnerability scans, and retrieving detailed reports.

**Human URL:** [https://pan.dev/prisma-airs-redteam/api/ai-integration/introduction/](https://pan.dev/prisma-airs-redteam/api/ai-integration/introduction/)

#### Tags:

 - AI Security, GenAI, LLM Security, Red Teaming, Vulnerability Assessment

#### Properties

- [Documentation](https://pan.dev/prisma-airs-redteam/api/ai-integration/introduction/)
- [GettingStarted](https://docs.paloaltonetworks.com/ai-runtime-security/ai-red-teaming/identify-ai-system-risks-with-ai-red-teaming/get-started-with-prisma-airs-ai-red-teaming)
- [OpenAPI](openapi/palo-alto-prisma-airs-ai-red-teaming-api-openapi-original.yml)

### Identity Security Posture Management API
A REST API within the SaaS Security Posture Management framework providing security-related metrics and configurations for user and service accounts across SaaS environments. The API enables security teams to monitor, analyze, and respond to identity-related risks by connecting users, permissions, activities, and security configurations.

**Human URL:** [https://pan.dev/sase/api/identity-sspm/](https://pan.dev/sase/api/identity-sspm/)

#### Tags:

 - Access Control, Identity Security, ITDR, MFA, SSPM

#### Properties

- [Documentation](https://pan.dev/sase/api/identity-sspm/)
- [OpenAPI](openapi/palo-alto-identity-security-posture-management-api-openapi-original.yml)

### SASE 5G Monitor Services API
REST APIs for monitoring 5G security services within the SASE platform. Provides telemetry, analytics, and health monitoring data for 5G network security deployments. Complements the SASE 5G Manage Services API by providing visibility into security service performance, traffic patterns, and threat detection metrics across 5G network environments. Uses OAuth 2.0 authentication.

**Human URL:** [https://pan.dev/sase/api/monitor-services-5g/](https://pan.dev/sase/api/monitor-services-5g/)

#### Tags:

 - 5G Security, Monitoring, Multi-Tenant, Network Analytics, Telecommunications

#### Properties

- [Documentation](https://pan.dev/sase/api/monitor-services-5g/)
- [OpenAPI](openapi/palo-alto-sase-5g-monitor-api-openapi-original.yml)

### Prisma SASE Service Status API
A public JSON API for monitoring Prisma SASE service health and status built on the Atlassian StatusPage platform. Provides endpoints for overall service status, individual component health, unresolved and recent incidents, and upcoming and active scheduled maintenance windows. Returns status indicators including operational, degraded performance, partial outage, and major outage. No authentication required.

**Human URL:** [https://pan.dev/sase/docs/saseservicestatusapi/](https://pan.dev/sase/docs/saseservicestatusapi/)

#### Tags:

 - Incidents, Maintenance, Monitoring, SASE, Status

#### Properties

- [Documentation](https://pan.dev/sase/docs/saseservicestatusapi/)

### Cross-Platform Service Status API
A public JSON API for monitoring the status of all Palo Alto Networks cloud services and products built on the Atlassian StatusPage platform. Provides endpoints for portfolio-wide status, individual product and service component health, unresolved and recent incidents, and scheduled maintenance events. Component statuses include operational, degraded performance, partial outage, and major outage. No authentication required.

**Human URL:** [https://pan.dev/cross-platform/docs/servicestatusapi/](https://pan.dev/cross-platform/docs/servicestatusapi/)

#### Tags:

 - Incidents, Maintenance, Monitoring, Platform Health, Status

#### Properties

- [Documentation](https://pan.dev/cross-platform/docs/servicestatusapi/)

### SASE Authentication Service API
The OAuth 2.0 authentication service that provides access tokens for all Prisma SASE platform APIs. Uses Client ID and Client Secret credentials to generate short-lived bearer tokens with a 15-minute lifespan. All SASE platform APIs including Prisma Access, SD-WAN, SSPM, and management services require tokens from this endpoint. Supports tenant service group (TSG) scoping for multi-tenant environments.

**Human URL:** [https://pan.dev/sase/api/auth/](https://pan.dev/sase/api/auth/)

#### Tags:

 - Access Tokens, Authentication, Identity, OAuth 2.0, SASE

#### Properties

- [Documentation](https://pan.dev/sase/api/auth/)
- [GettingStarted](https://pan.dev/sase/docs/getstarted/)

### Expedition API (Deprecated)
A RESTful API for the Expedition 2.0 migration tool enabling programmatic firewall configuration migration from third-party vendors, policy optimization, and rule analysis. Supported migration from Check Point, Cisco ASA, Fortinet, and other firewall platforms to PAN-OS. Built on the Laravel PHP framework. Expedition reached end-of-support in January 2025. Developers should use Strata Cloud Manager migration tools for new migration workflows.

**Human URL:** [https://pan.dev/expedition/docs/expedition_apiint/](https://pan.dev/expedition/docs/expedition_apiint/)

#### Tags:

 - Configuration, Deprecated, Firewall, Migration, Policy Optimization

#### Properties

- [Documentation](https://pan.dev/expedition/docs/expedition_apiint/)
- [GettingStarted](https://pan.dev/expedition/docs/expedition_workflow/)

### SASE Multitenant Notifications API
A REST API for managing notifications and notification profiles across SASE multitenant environments. Supports creating and managing notification profiles, configuring webhook destinations, testing webhook connectivity, and retrieving notifications for security incidents, platform announcements, Prisma Access dataplane upgrades, and certificate expiry warnings across tenant hierarchies. Uses OAuth 2.0 authentication.

**Human URL:** [https://pan.dev/sase/api/mt-notifications/](https://pan.dev/sase/api/mt-notifications/)

#### Tags:

 - Alerts, Multi-Tenant, Notifications, SASE, Webhooks

#### Properties

- [Documentation](https://pan.dev/sase/api/mt-notifications/)
- [OpenAPI](openapi/palo-alto-sase-multitenant-notifications-api-openapi-original.yml)

### SASE Multitenant Interconnect API
A REST API for managing service provider interconnect configurations within the SASE platform. Enables using service provider backbones for directing Prisma Access egress traffic instead of relying on public cloud providers. Supports managing traffic routing preferences on a per-service-provider and per-region basis for telecommunications partners including BT, Orange, and AT&T. Uses OAuth 2.0 authentication.

**Human URL:** [https://pan.dev/sase/api/mt-interconnect/multitenant-interconnect-apis/](https://pan.dev/sase/api/mt-interconnect/multitenant-interconnect-apis/)

#### Tags:

 - Interconnect, Multi-Tenant, Network Routing, SASE, Service Provider

#### Properties

- [Documentation](https://pan.dev/sase/api/mt-interconnect/multitenant-interconnect-apis/)
- [OpenAPI](openapi/palo-alto-sase-multitenant-interconnect-api-openapi-original.yml)

### Cloud Identity Engine API
A REST API for the Cloud Identity Engine (CIE) Directory Sync Service that aggregates, normalizes, and provides access to enterprise identity data from multiple directory sources through a unified API. Supports synchronization of user, group, and organizational unit data from Active Directory, Azure Active Directory, Okta, Google Workspace, and PingFederate. Provides enriched user context including device, location, and logon event data for identity-aware security policies.

**Human URL:** [https://pan.dev/scm/api/config/ciedss/ciedss/](https://pan.dev/scm/api/config/ciedss/ciedss/)

#### Tags:

 - Active Directory, Azure AD, Cloud Identity, Directory Sync, Identity

#### Properties

- [Documentation](https://pan.dev/scm/api/config/ciedss/ciedss/)
- [GettingStarted](https://pan.dev/scm/docs/getstarted/)
- [OpenAPI](openapi/palo-alto-cloud-identity-engine-api-openapi-original.yml)

### Prisma Cloud MSSP API
A REST API for managing Prisma Cloud multi-tenant MSSP deployments including tenant provisioning, license management, policy group administration, and cross-tenant operations. Supports creating and managing managed tenants, allocating license pools, configuring shared policy groups, and performing seamless login across tenant boundaries. Designed for Managed Security Service Providers operating Prisma Cloud on behalf of multiple customers.

**Human URL:** [https://pan.dev/prisma-cloud/api/mssp/prisma-cloud-managed-security-service-provider-mssp/](https://pan.dev/prisma-cloud/api/mssp/prisma-cloud-managed-security-service-provider-mssp/)

#### Tags:

 - Cloud Security, Licensing, Managed Services, MSSP, Multi-Tenant

#### Properties

- [Documentation](https://pan.dev/prisma-cloud/api/mssp/prisma-cloud-managed-security-service-provider-mssp/)
- [OpenAPI](openapi/palo-alto-prisma-cloud-mssp-api-openapi-original.json)

### VM-Series Licensing API
A REST API for licensing VM-Series virtual firewalls that do not have direct internet access to the Palo Alto Networks license server. Supports automated license activation, deactivation, and management for VM-Series deployments in air-gapped or restricted network environments.

**Human URL:** [https://docs.paloaltonetworks.com/vm-series/10-2/vm-series-deployment/license-the-vm-series-firewall/vm-series-models/licensing-api](https://docs.paloaltonetworks.com/vm-series/10-2/vm-series-deployment/license-the-vm-series-firewall/vm-series-models/licensing-api)

#### Tags:

 - Automation, Firewall, Licensing, Virtualization, VM-Series

#### Properties

- [Documentation](https://docs.paloaltonetworks.com/vm-series/10-2/vm-series-deployment/license-the-vm-series-firewall/vm-series-models/licensing-api)

### Prisma Access Insights API
A REST API for querying the health and performance of Prisma Access network deployments across multiple API versions (v1.0, v2.0, v3.0). Supports data resource queries for tunnel status, bandwidth utilization, user connectivity, and network health metrics across Prisma Access locations and tenants.

**Human URL:** [https://pan.dev/access/api/insights/](https://pan.dev/access/api/insights/)

#### Tags:

 - Analytics, Monitoring, Network Health, Prisma Access, SASE

#### Properties

- [Documentation](https://pan.dev/access/api/insights/)
- [OpenAPI](openapi/palo-alto-prisma-access-insights-api-openapi-original.yml)

## Common Properties

- [Portal](https://pan.dev/)
- [Documentation](https://docs.paloaltonetworks.com/)
- [API Documentation](https://docs.paloaltonetworks.com/develop/api)
- [Website](https://www.paloaltonetworks.com)
- [Support](https://www.paloaltonetworks.com/services/support)
- [Blog](https://www.paloaltonetworks.com/blog/)
- [Status](https://status.paloaltonetworks.com/)
- [Forum](https://live.paloaltonetworks.com/)
- [Security Advisories](https://security.paloaltonetworks.com/)
- [GitHub - PaloAltoNetworks](https://github.com/PaloAltoNetworks)
- [GitHub - Demisto](https://github.com/demisto)
- [GitHub - Unit42](https://github.com/pan-unit42)
- [PAN-OS Python SDK](https://github.com/PaloAltoNetworks/pan-os-python)
- [PAN-OS Go SDK](https://github.com/PaloAltoNetworks/pango)
- [PAN Python](https://github.com/PaloAltoNetworks/pan-python)
- [PAN-OS PHP](https://github.com/PaloAltoNetworks/pan-os-php)
- [Prisma SASE Python SDK](https://github.com/PaloAltoNetworks/prisma-sase-sdk-python)
- [Cortex Cloud Go SDK](https://github.com/PaloAltoNetworks/cortex-cloud-go)
- [Cloud NGFW AWS Go SDK](https://github.com/PaloAltoNetworks/cloud-ngfw-aws-go)
- [Cortex CLI](https://github.com/PaloAltoNetworks/homebrew-cortexcli)
- [Upgrade Assurance CLI](https://github.com/PaloAltoNetworks/upgrade-assurance-cli)
- [Terraform - PAN-OS](https://registry.terraform.io/providers/PaloAltoNetworks/panos/latest)
- [Terraform - SCM](https://registry.terraform.io/providers/PaloAltoNetworks/scm/latest)
- [Terraform - Cortex Cloud](https://registry.terraform.io/providers/PaloAltoNetworks/cortexcloud/latest)
- [Terraform - Prisma SD-WAN](https://registry.terraform.io/providers/PaloAltoNetworks/prismasdwan/latest)
- [Terraform - Cloud NGFW AWS](https://registry.terraform.io/providers/PaloAltoNetworks/cloudngfwaws/latest)
- [Terraform - Prisma Cloud](https://registry.terraform.io/providers/PaloAltoNetworks/prismacloud/latest)
- [Terraform - Prisma Cloud Compute](https://registry.terraform.io/providers/PaloAltoNetworks/prismacloudcompute/latest)
- [Terraform Namespace](https://registry.terraform.io/namespaces/PaloAltoNetworks)
- [Upgrade Assurance](https://github.com/PaloAltoNetworks/pan-os-upgrade-assurance)
- [Prisma Cloud Scan](https://github.com/PaloAltoNetworks/prisma-cloud-scan)
- [Cobra Tool](https://github.com/PaloAltoNetworks/cobra-tool)
- [Gallery](https://gallery.pan.dev/)
- [Ansible Collection](https://galaxy.ansible.com/paloaltonetworks/panos)
- [Training](https://www.paloaltonetworks.com/services/education)
- [Learning Center](https://learn.paloaltonetworks.com)
- [Privacy Policy](https://www.paloaltonetworks.com/legal/privacy)
- [Terms of Service](https://www.paloaltonetworks.com/legal)
- [X](https://x.com/PaloAltoNtwks)
- [YouTube](https://www.youtube.com/@pabornetworks)
- [LinkedIn](https://www.linkedin.com/company/palo-alto-networks)
- [Developer Blog](https://medium.com/palo-alto-networks-developer-blog)
- [Release Notes](https://docs.paloaltonetworks.com/release-notes)
- [SASE ChangeLog](https://pan.dev/sase/docs/release-notes/changelog/)
- [SCM ChangeLog](https://pan.dev/scm/docs/release-notes/changelog/)
- [Postman Workspace](https://www.postman.com/paloaltonetworks)
- [Slack Community](https://start.paloaltonetworks.com/join-our-slack-community)
- [Unit 42 Blog](https://unit42.paloaltonetworks.com/)
- [Cortex Portal](https://cortex.pan.dev/)
- [XSOAR Portal](https://xsoar.pan.dev/)
- [Software Firewall Documentation](https://pan.dev/swfw/)
- [Splunk Integration](https://splunkbase.splunk.com/app/2757)
- [Partner Program](https://www.paloaltonetworks.com/partners)

## Features

| Name | Description |
|------|-------------|
| Zero Trust Network Security | Next-generation firewall policies with application, user, and content awareness for enforcing zero trust across on-premises and cloud environments. |
| AI-Powered Threat Prevention | Machine learning and deep learning models that detect and prevent known and unknown threats in real time across network traffic, files, and URLs. |
| Cloud-Native Application Protection | Full lifecycle cloud security spanning code, build, deploy, and runtime with CSPM, CWPP, code security, and data security posture management. |
| Security Orchestration and Automation | Automated incident response with playbooks, integrations, and case management through Cortex XSOAR and XSIAM platforms. |
| Extended Detection and Response | Cross-data-source threat detection correlating endpoint, network, cloud, and identity data through Cortex XDR for unified security operations. |
| AI Runtime Security | Real-time scanning of AI application prompts and responses for prompt injection, data leakage, toxic content, and other AI-specific threats. |
| Secure Access Service Edge | Cloud-delivered security and networking combining Prisma Access, SD-WAN, ZTNA, and cloud SWG for secure access from any location. |
| Attack Surface Management | Continuous discovery and monitoring of internet-facing assets and exposures through Cortex Xpanse for external attack surface visibility. |
| Infrastructure as Code Security | Automated security scanning of Terraform, CloudFormation, Kubernetes, and other IaC templates for misconfigurations before deployment. |
| Digital Experience Monitoring | End-to-end visibility into application performance and user experience across SASE connections with Autonomous DEM. |
| Threat Intelligence | Comprehensive threat intelligence through Threat Vault, WildFire malware analysis, DNS Security, and Unit 42 research for proactive defense. |
| Multi-Tenant Management | Hierarchical tenant management with delegated administration, aggregate monitoring, and shared policy for MSSPs and large enterprises. |

## Use Cases

| Name | Description |
|------|-------------|
| SOC Automation | Automate alert triage, incident investigation, and response actions using Cortex XDR, XSOAR playbooks, and XSIAM correlation rules. |
| Firewall Policy Management | Programmatically manage security policies, address objects, and NAT rules across PAN-OS firewalls and Panorama using REST or XML APIs. |
| Cloud Security Posture | Monitor and remediate cloud misconfigurations, compliance violations, and vulnerabilities across AWS, Azure, and GCP using Prisma Cloud APIs. |
| Threat Hunting | Query threat intelligence databases, submit suspicious files for analysis, and correlate IOCs across Threat Vault, WildFire, and DNS Security. |
| SASE Deployment Automation | Automate Prisma Access remote network onboarding, SD-WAN site configuration, and ZTNA connector deployment using SASE platform APIs. |
| DevSecOps Pipeline Integration | Embed security scanning into CI/CD pipelines with Prisma Cloud code security APIs for IaC scanning, SCA, and secrets detection. |
| AI Application Security | Integrate Prisma AIRS API Intercept into AI application code to scan LLM prompts and responses for security threats in real time. |
| Compliance Monitoring | Continuously assess cloud infrastructure against CIS benchmarks, PCI DSS, HIPAA, SOC 2, and custom compliance standards using Prisma Cloud. |
| Log Forwarding and SIEM Integration | Forward security logs from firewalls and cloud services to Splunk, QRadar, and other SIEMs using Strata Logging Service APIs. |
| Multi-Tenant Security Operations | Manage security across tenant hierarchies with aggregate monitoring, shared notifications, and delegated administration for MSSPs. |

## Integrations

| Name | Description |
|------|-------------|
| Splunk | Splunk App and Add-on for ingesting PAN-OS, Prisma Cloud, and Cortex logs with pre-built dashboards, reports, and data models. |
| Terraform | Official Terraform providers for PAN-OS, Strata Cloud Manager, Prisma Cloud, Cloud NGFW, and Prisma Cloud Compute for infrastructure as code. |
| Ansible | Official Ansible collection with 60+ modules for PAN-OS firewall and Panorama configuration automation. |
| AWS | Cloud NGFW for AWS, VM-Series on AWS, Prisma Cloud AWS account onboarding, and CloudFormation template support. |
| Azure | Cloud NGFW for Azure, VM-Series on Azure, Prisma Cloud Azure subscription onboarding, and Azure AD integration. |
| Google Cloud | VM-Series on GCP, Prisma Cloud GCP project onboarding, and Google Workspace integration with Cloud Identity Engine. |
| ServiceNow | Cortex XSOAR integration for bi-directional ticket synchronization and automated incident response workflows. |
| Slack | Cortex XSOAR Slack integration for alert notifications, war room collaboration, and ChatOps-driven security operations. |
| Active Directory | Cloud Identity Engine directory sync with on-premises Active Directory for user-to-IP mapping and identity-aware firewall policies. |
| Okta | Cloud Identity Engine integration with Okta for SSO user context and identity-aware security policy enforcement. |

## Solutions

| Name | Description |
|------|-------------|
| Strata Network Security Platform | Next-generation firewall platform including PAN-OS hardware and software firewalls, Panorama management, and Strata Cloud Manager. |
| Prisma Cloud | Cloud-native application protection platform with CSPM, CWPP, code security, DSPM, and CIEM for multi-cloud environments. |
| Prisma SASE | Secure access service edge platform combining Prisma Access, SD-WAN, ZTNA, Autonomous DEM, and cloud SWG. |
| Cortex SecOps | Security operations platform with Cortex XDR for detection and response, XSOAR for automation, and XSIAM for AI-driven SOC. |
| Prisma AIRS | AI runtime security platform for securing generative AI applications with API Intercept scanning and AI Red Teaming. |
| Unit 42 Threat Intelligence | Threat research and intelligence services including Threat Vault, WildFire malware analysis, DNS Security, and security advisory feeds. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AIOps NGFW BPA API](openapi/palo-alto-aiops-ngfw-bpa-api-openapi-original.yml)
- [Autonomous DEM API](openapi/palo-alto-autonomous-dem-api-openapi-original.yml)
- [Cloud Identity Engine API](openapi/palo-alto-cloud-identity-engine-api-openapi-original.yml)
- [Cloud NGFW API](openapi/palo-alto-cloud-ngfw-api-openapi-original.yml)
- [Cortex XDR API](openapi/palo-alto-cortex-xdr-api-openapi-original.yml)
- [Cortex Xpanse API](openapi/palo-alto-cortex-xpanse-api-openapi-original.yml)
- [Cortex XSIAM API](openapi/palo-alto-cortex-xsiam-api-openapi-original.yml)
- [Cortex XSOAR API](openapi/palo-alto-cortex-xsoar-api-openapi-original.yml)
- [DLP API](openapi/palo-alto-dlp-api-openapi-original.yml)
- [DNS Security API](openapi/palo-alto-dns-security-api-openapi-original.yml)
- [Email DLP API](openapi/palo-alto-email-dlp-api-openapi-original.yml)
- [Identity Security Posture Management API](openapi/palo-alto-identity-security-posture-management-api-openapi-original.yml)
- [IoT Security API](openapi/palo-alto-iot-security-api-openapi-original.yml)
- [PAN-OS REST API](openapi/palo-alto-pan-os-rest-api-openapi-original.yml)
- [Prisma Access API](openapi/palo-alto-prisma-access-api-openapi-original.yml)
- [Prisma Access Browser API](openapi/palo-alto-prisma-access-browser-api-openapi-original.yml)
- [Prisma Access Insights API](openapi/palo-alto-prisma-access-insights-api-openapi-original.yml)
- [Prisma AIRS AI Red Teaming API](openapi/palo-alto-prisma-airs-ai-red-teaming-api-openapi-original.yml)
- [Prisma AIRS API](openapi/palo-alto-prisma-airs-api-openapi-original.yml)
- [Prisma Cloud Code Security API](openapi/palo-alto-prisma-cloud-code-security-api-openapi-original.yml)
- [Prisma Cloud Compute API](openapi/palo-alto-prisma-cloud-compute-api-openapi-original.yml)
- [Prisma Cloud CSPM API](openapi/palo-alto-prisma-cloud-cspm-api-openapi-original.yml)
- [Prisma Cloud DSPM API](openapi/palo-alto-prisma-cloud-dspm-api-openapi-original.yml)
- [Prisma Cloud MSSP API](openapi/palo-alto-prisma-cloud-mssp-api-openapi-original.json)
- [Prisma SD-WAN API](openapi/palo-alto-prisma-sd-wan-api-openapi-original.yml)
- [SaaS Security API](openapi/palo-alto-saas-security-api-openapi-original.yml)
- [SASE 5G API](openapi/palo-alto-sase-5g-api-openapi-original.yml)
- [SASE 5G Monitor API](openapi/palo-alto-sase-5g-monitor-api-openapi-original.yml)
- [SASE Aggregate Monitoring API](openapi/palo-alto-sase-aggregate-monitoring-api-openapi-original.yml)
- [SASE Config Orchestration API](openapi/palo-alto-sase-config-orchestration-api-openapi-original.yml)
- [SASE IAM API](openapi/palo-alto-sase-iam-api-openapi-original.yml)
- [SASE Multitenant Interconnect API](openapi/palo-alto-sase-multitenant-interconnect-api-openapi-original.yml)
- [SASE Multitenant Notifications API](openapi/palo-alto-sase-multitenant-notifications-api-openapi-original.yml)
- [SASE Subscription API](openapi/palo-alto-sase-subscription-api-openapi-original.yml)
- [SASE Tenancy API](openapi/palo-alto-sase-tenancy-api-openapi-original.yml)
- [Security Advisory API](openapi/palo-alto-security-advisory-api-openapi-original.yml)
- [SSPM API](openapi/palo-alto-sspm-api-openapi-original.yml)
- [Strata Cloud Manager API](openapi/palo-alto-strata-cloud-manager-api-openapi-original.yml)
- [Strata Logging Service API](openapi/palo-alto-strata-logging-service-api-openapi-original.yml)
- [Threat Vault API](openapi/palo-alto-threat-vault-api-openapi-original.yml)
- [WildFire API](openapi/palo-alto-wildfire-api-openapi-original.yml)
- [ZTNA Connector API](openapi/palo-alto-ztna-connector-api-openapi-original.yml)

### AsyncAPI

- [Cortex XDR Webhooks](asyncapi/palo-alto-cortex-xdr-webhooks-asyncapi-original.yml)
- [Cortex XSIAM Data Ingestion](asyncapi/palo-alto-cortex-xsiam-data-ingestion-asyncapi-original.yml)
- [Prisma Cloud Webhooks](asyncapi/palo-alto-prisma-cloud-webhooks-asyncapi-original.yml)
- [SASE Notifications](asyncapi/palo-alto-sase-notifications-asyncapi-original.yml)
- [Strata Logging Forwarding](asyncapi/palo-alto-strata-logging-forwarding-asyncapi-original.yml)

### JSON Schema

423 JSON Schema files defining request/response structures across all APIs. See the [json-schema/](json-schema/) directory.

### JSON Structure

423 JSON Structure files providing simplified structural representations. See the [json-structure/](json-structure/) directory.

### JSON-LD

54 JSON-LD context files for linked data semantics. See the [json-ld/](json-ld/) directory.

### Examples

423 example JSON files demonstrating API request/response payloads. See the [examples/](examples/) directory.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AIOps NGFW BPA](capabilities/shared/aiops-ngfw-bpa.yaml) -- 9 operations
- [Autonomous DEM](capabilities/shared/autonomous-dem.yaml) -- 25 operations
- [Cloud Identity Engine](capabilities/shared/cloud-identity-engine.yaml) -- 17 operations
- [Cloud NGFW](capabilities/shared/cloud-ngfw.yaml) -- 53 operations
- [Cortex XDR](capabilities/shared/cortex-xdr.yaml) -- 43 operations
- [Cortex Xpanse](capabilities/shared/cortex-xpanse.yaml) -- 26 operations
- [Cortex XSIAM](capabilities/shared/cortex-xsiam.yaml) -- 23 operations
- [Cortex XSOAR](capabilities/shared/cortex-xsoar.yaml) -- 33 operations
- [DLP](capabilities/shared/dlp.yaml) -- 21 operations
- [DNS Security](capabilities/shared/dns-security.yaml) -- 11 operations
- [Email DLP](capabilities/shared/email-dlp.yaml) -- 15 operations
- [Identity Security Posture](capabilities/shared/identity-security-posture.yaml) -- 79 operations
- [IoT Security](capabilities/shared/iot-security.yaml) -- 29 operations
- [PAN-OS](capabilities/shared/pan-os.yaml) -- 54 operations
- [Prisma Access](capabilities/shared/prisma-access.yaml) -- 33 operations
- [Prisma Access Browser](capabilities/shared/prisma-access-browser.yaml) -- 25 operations
- [Prisma Access Insights](capabilities/shared/prisma-access-insights.yaml) -- 15 operations
- [Prisma AIRS](capabilities/shared/prisma-airs.yaml) -- 13 operations
- [Prisma AIRS Red Teaming](capabilities/shared/prisma-airs-red-teaming.yaml) -- 28 operations
- [Prisma Cloud Code Security](capabilities/shared/prisma-cloud-code-security.yaml) -- 50 operations
- [Prisma Cloud Compute](capabilities/shared/prisma-cloud-compute.yaml) -- 54 operations
- [Prisma Cloud CSPM](capabilities/shared/prisma-cloud-cspm.yaml) -- 68 operations
- [Prisma Cloud DSPM](capabilities/shared/prisma-cloud-dspm.yaml) -- 56 operations
- [Prisma Cloud MSSP](capabilities/shared/prisma-cloud-mssp.yaml) -- 118 operations
- [Prisma SD-WAN](capabilities/shared/prisma-sd-wan.yaml) -- 83 operations
- [SaaS Security](capabilities/shared/saas-security.yaml) -- 35 operations
- [SASE 5G](capabilities/shared/sase-5g.yaml) -- 70 operations
- [SASE Aggregate Monitoring](capabilities/shared/sase-aggregate-monitoring.yaml) -- 42 operations
- [SASE Config Orchestration](capabilities/shared/sase-config-orchestration.yaml) -- 31 operations
- [SASE IAM](capabilities/shared/sase-iam.yaml) -- 45 operations
- [SASE Multitenant Interconnect](capabilities/shared/sase-multitenant-interconnect.yaml) -- 76 operations
- [SASE Multitenant Notifications](capabilities/shared/sase-multitenant-notifications.yaml) -- 35 operations
- [SASE Subscription](capabilities/shared/sase-subscription.yaml) -- 11 operations
- [SASE Tenancy](capabilities/shared/sase-tenancy.yaml) -- 24 operations
- [Security Advisory](capabilities/shared/security-advisory.yaml) -- 11 operations
- [SSPM](capabilities/shared/sspm.yaml) -- 36 operations
- [Strata Cloud Manager](capabilities/shared/strata-cloud-manager.yaml) -- 116 operations
- [Strata Logging Service](capabilities/shared/strata-logging-service.yaml) -- 47 operations
- [Threat Vault](capabilities/shared/threat-vault.yaml) -- 29 operations
- [WildFire](capabilities/shared/wildfire.yaml) -- 26 operations
- [ZTNA Connector](capabilities/shared/ztna-connector.yaml) -- 59 operations

### Workflow Capabilities

| Workflow | APIs Combined |
|----------|--------------|
| [AI Security](capabilities/ai-security.yaml) | prisma-airs, prisma-airs-red-teaming |
| [Browser Security](capabilities/browser-security.yaml) | prisma-access-browser |
| [Cloud Security Posture](capabilities/cloud-security-posture.yaml) | prisma-cloud-cspm, prisma-cloud-code-security, prisma-cloud-dspm, prisma-cloud-mssp |
| [Data Protection](capabilities/data-protection.yaml) | dlp, email-dlp, saas-security, sspm, identity-security-posture |
| [Identity and Access Management](capabilities/identity-and-access.yaml) | sase-iam, sase-tenancy, sase-subscription, cloud-identity-engine |
| [Incident Response](capabilities/incident-response.yaml) | cortex-xdr, cortex-xsiam, cortex-xsoar, cortex-xpanse |
| [Monitoring and Observability](capabilities/monitoring-and-observability.yaml) | autonomous-dem, sase-aggregate-monitoring, strata-logging-service, aiops-ngfw-bpa, sase-multitenant-notifications |
| [Network Security Configuration](capabilities/network-security-config.yaml) | pan-os, strata-cloud-manager, cloud-ngfw |
| [Secure Access](capabilities/secure-access.yaml) | prisma-access, ztna-connector, prisma-sd-wan, sase-config-orchestration, sase-5g, sase-multitenant-interconnect |
| [Threat Intelligence](capabilities/threat-intelligence.yaml) | threat-vault, wildfire, dns-security, security-advisory |

## Vocabulary

- [Palo Alto Networks Vocabulary](vocabulary/palo-alto-networks-vocabulary.yaml) -- Unified taxonomy mapping 36 resources, 17 actions, 10 workflows, and 21 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Palo Alto Networks Spectral Rules](rules/palo-alto-networks-spectral-rules.yml) -- 69 rules enforcing Palo Alto Networks API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
