# VMware (vmware)

Collection of VMware APIs for cloud infrastructure, virtualization, and management solutions including vSphere, NSX, vCloud Director, Tanzu, and Aria operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vmware/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vmware/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cloud Computing
- Container Management
- Hybrid Cloud
- Infrastructure
- Virtualization

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### vSphere API

API for managing VMware vSphere virtualization platform, including VMs, hosts, and datastores.

- **Human URL:** [https://developer.vmware.com/apis/vsphere-automation/latest/](https://developer.vmware.com/apis/vsphere-automation/latest/)
- **Base URL:** `https://{{vcenter}}/api`

#### Tags

- Data Center
- Hypervisor
- Virtualization
- VM Management

#### Properties

- [Documentation](https://developer.vmware.com/docs/vsphere-automation/latest/)
- [OpenAPI](openapi/vmware-vsphere-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://developer.vmware.com/apis/vsphere-automation/latest/openapi/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.vmware.com/docs/vsphere-automation/latest/authentication/)
- [API Reference](https://developer.broadcom.com/xapis/vsphere-automation-api/latest/)
- [JSON Schema](json-schema/vmware-virtual-machine-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/vmware-vsphere-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### vSphere Web Services API

Comprehensive SOAP-based API providing access to all vSphere management functionality including virtual machines, hosts, clusters, networking, and storage.

- **Human URL:** [https://developer.broadcom.com/xapis/vsphere-web-services-api/latest/](https://developer.broadcom.com/xapis/vsphere-web-services-api/latest/)
- **Base URL:** `https://{{vcenter}}/sdk`

#### Tags

- Data Center
- SOAP
- Virtualization
- VM Management

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vsphere-web-services-api/latest/)
- [SDK](https://github.com/vmware/vsphere-automation-sdk-java)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Virtual Infrastructure JSON API

HTTP and JSON based wire protocol as an alternative to SOAP and XML for vCenter Server 8.0 Update 1 and later, documented via OpenAPI 3.0 specification.

- **Human URL:** [https://developer.broadcom.com/xapis/virtual-infrastructure-json-api/latest/](https://developer.broadcom.com/xapis/virtual-infrastructure-json-api/latest/)
- **Base URL:** `https://{{vcenter}}/sdk/vim25/8.0.1.0`

#### Tags

- JSON
- REST
- vCenter
- Virtualization

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/virtual-infrastructure-json-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### vCloud Director API

API for VMware vCloud Director cloud service delivery platform.

- **Human URL:** [https://developer.vmware.com/apis/vmware-cloud-director/latest/](https://developer.vmware.com/apis/vmware-cloud-director/latest/)
- **Base URL:** `https://{{vcd-host}}/api`

#### Tags

- Cloud Management
- Multi-Tenancy
- Service Provider

#### Properties

- [Documentation](https://developer.vmware.com/docs/vmware-cloud-director/latest/)
- [OpenAPI](https://developer.vmware.com/apis/vmware-cloud-director/latest/openapi/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [API Reference](https://developer.broadcom.com/xapis/vmware-cloud-director-openapi/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NSX-T Data Center API

API for NSX-T network virtualization and security platform.

- **Human URL:** [https://developer.vmware.com/apis/nsx-t/latest/](https://developer.vmware.com/apis/nsx-t/latest/)
- **Base URL:** `https://{{nsx-manager}}/api/v1`

#### Tags

- Load Balancing
- Micro-Segmentation
- Network Virtualization
- Security

#### Properties

- [Documentation](https://developer.vmware.com/docs/nsx-t/latest/)
- [OpenAPI](https://developer.vmware.com/apis/nsx-t/latest/openapi/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [API Reference](https://developer.broadcom.com/xapis/nsx-t-data-center-rest-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NSX-T Global Manager API

API for managing NSX Federation with centralized configuration of multiple NSX deployments across sites.

- **Human URL:** [https://developer.broadcom.com/xapis/nsx-t-data-center-global-manager-rest-api/latest/](https://developer.broadcom.com/xapis/nsx-t-data-center-global-manager-rest-api/latest/)
- **Base URL:** `https://{{global-manager}}/global-manager/api/v1`

#### Tags

- Federation
- Multi-Site
- Network Virtualization
- Security

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/nsx-t-data-center-global-manager-rest-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NSX Intelligence API

API for NSX Intelligence and Application Platform providing network traffic data collection, ingestion, and correlation capabilities.

- **Human URL:** [https://developer.broadcom.com/xapis/nsx-intelligence-and-application-platform-apis/latest/](https://developer.broadcom.com/xapis/nsx-intelligence-and-application-platform-apis/latest/)
- **Base URL:** `https://{{nsx-manager}}/napp/api/v1`

#### Tags

- Network Intelligence
- Security Analytics
- Traffic Analysis

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/nsx-intelligence-and-application-platform-apis/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NSX Autonomous Edge API

REST API for NSX Autonomous Edge providing network virtualization capabilities for edge deployments using a resource-oriented architecture with JSON encoding.

- **Human URL:** [https://developer.broadcom.com/xapis/nsx-autonomous-edge-rest-api/latest/](https://developer.broadcom.com/xapis/nsx-autonomous-edge-rest-api/latest/)
- **Base URL:** `https://{{nsx-edge}}/api/v1`

#### Tags

- Edge Computing
- Network Virtualization
- SD-WAN

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/nsx-autonomous-edge-rest-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### vRealize Automation API

API for automating IT service delivery and cloud infrastructure management.

- **Human URL:** [https://developer.vmware.com/apis/vrealize-automation/latest/](https://developer.vmware.com/apis/vrealize-automation/latest/)
- **Base URL:** `https://{{vra-host}}/automation-api`

#### Tags

- Automation
- Infrastructure as Code
- Orchestration
- Self-Service

#### Properties

- [Documentation](https://developer.vmware.com/docs/vrealize-automation/latest/)
- [OpenAPI](https://developer.vmware.com/apis/vrealize-automation/latest/openapi/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Code Examples](https://github.com/vmware/vrealize-automation-samples)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Cloud on AWS API

API for managing VMware Cloud on AWS infrastructure.

- **Human URL:** [https://developer.vmware.com/apis/vmc/latest/](https://developer.vmware.com/apis/vmc/latest/)
- **Base URL:** `https://vmc.vmware.com/vmc/api`

#### Tags

- AWS
- Cloud Services
- Hybrid Cloud
- SDDC

#### Properties

- [Documentation](https://developer.vmware.com/docs/vmc/latest/)
- [OpenAPI](https://developer.vmware.com/apis/vmc/latest/openapi/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://developer.vmware.com/docs/vmc/latest/getting-started/)
- [API Reference](https://developer.broadcom.com/xapis/nsx-vmc-policy/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tanzu Kubernetes Grid API

API for managing enterprise-ready Kubernetes clusters.

- **Human URL:** [https://developer.vmware.com/apis/tanzu/](https://developer.vmware.com/apis/tanzu/)
- **Base URL:** `https://{{tkg-endpoint}}/api`

#### Tags

- Cloud Native
- Containers
- DevOps
- Kubernetes

#### Properties

- [Documentation](https://docs.vmware.com/en/VMware-Tanzu-Kubernetes-Grid/index.html)
- [C L I](https://docs.vmware.com/en/VMware-Tanzu-Kubernetes-Grid/latest/vmware-tanzu-kubernetes-grid/cli-reference.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### vRealize Operations API

API for IT operations management and performance monitoring.

- **Human URL:** [https://developer.vmware.com/apis/vrealize-operations/latest/](https://developer.vmware.com/apis/vrealize-operations/latest/)
- **Base URL:** `https://{{vrops-host}}/suite-api/api`

#### Tags

- Analytics
- Monitoring
- Operations
- Performance

#### Properties

- [Documentation](https://developer.vmware.com/docs/vrealize-operations/latest/)
- [OpenAPI](https://developer.vmware.com/apis/vrealize-operations/latest/openapi/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workspace ONE API

API for unified endpoint management and digital workspace platform.

- **Human URL:** [https://developer.vmware.com/apis/workspace-one/](https://developer.vmware.com/apis/workspace-one/)
- **Base URL:** `https://{{ws1-host}}/api`

#### Tags

- Endpoint Management
- Enterprise Mobility
- Identity
- Mobile Device Management

#### Properties

- [Documentation](https://developer.vmware.com/docs/workspace-one/)
- [API Reference](https://developer.vmware.com/apis/workspace-one/latest/reference/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Cloud Foundation API

API for managing the full VMware Cloud Foundation stack including SDDC Manager and Cloud Builder for automated lifecycle management of private cloud infrastructure.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-cloud-foundation-api/latest/](https://developer.broadcom.com/xapis/vmware-cloud-foundation-api/latest/)
- **Base URL:** `https://{{sddc-manager}}/v1`

#### Tags

- Cloud Foundation
- Hyperconverged Infrastructure
- Lifecycle Management
- SDDC

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-cloud-foundation-api/latest/)
- [Documentation](https://techdocs.broadcom.com/us/en/vmware-cis/vcf/vcf-9-0-and-later/9-0/administration-sdks-cli-and-tools/about-vmware-cloud-foundation-development/vcf-apis-and-scripts.html)
- [SDK](https://github.com/vmware/vcf-sdk-java)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Horizon Server API

API for managing VMware Horizon virtual desktop and application delivery platform including pools, farms, desktops, and sessions.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-horizon-server-api/latest/](https://developer.broadcom.com/xapis/vmware-horizon-server-api/latest/)
- **Base URL:** `https://{{horizon-server}}/rest`

#### Tags

- Desktop Virtualization
- Remote Access
- VDI
- Virtual Desktop

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-horizon-server-api/latest/)
- [Documentation](https://techdocs.broadcom.com/us/en/vmware-cis/horizon.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### vSAN Management API

API for managing VMware vSAN software-defined storage including cluster configuration, disk management, health monitoring, and performance analytics.

- **Human URL:** [https://developer.broadcom.com/xapis/vsan-management-api/latest/](https://developer.broadcom.com/xapis/vsan-management-api/latest/)
- **Base URL:** `https://{{vcenter}}/vsanHealth`

#### Tags

- Data Management
- Hyper-Converged
- Storage
- vSAN

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vsan-management-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Aria Operations for Logs API

REST API for VMware Aria Operations for Logs providing programmatic access to log data ingestion, querying, aggregation, and platform configuration.

- **Human URL:** [https://developer.broadcom.com/xapis/vrealize-log-insight-api/latest/](https://developer.broadcom.com/xapis/vrealize-log-insight-api/latest/)
- **Base URL:** `https://{{log-insight-host}}:9543/api/v2`

#### Tags

- Analytics
- Log Management
- Monitoring
- Observability

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vrealize-log-insight-api/latest/)
- [Documentation](https://techdocs.broadcom.com/us/en/vmware-cis/aria/aria-operations-for-logs/8-18/developer-resources-for-vmware-aria-operations-for-logs-8-18/the-vrealize-log-insight-rest-api.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Aria Operations for Networks API

API for network visibility, analytics, and troubleshooting providing access to application discovery, microsegmentation planning, and network flow analysis.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-aria-operations-for-networks-api/latest/](https://developer.broadcom.com/xapis/vmware-aria-operations-for-networks-api/latest/)
- **Base URL:** `https://{{vrni-host}}/api/ni`

#### Tags

- Microsegmentation
- Network Analytics
- Network Monitoring
- Troubleshooting

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-aria-operations-for-networks-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Aria Suite Lifecycle API

REST API for managing the lifecycle of VMware Aria suite products including deployment, upgrade, patching, and configuration management.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-aria-suite-lifecycle-rest-api/latest/](https://developer.broadcom.com/xapis/vmware-aria-suite-lifecycle-rest-api/latest/)
- **Base URL:** `https://{{lcm-host}}/lcm/api`

#### Tags

- Automation
- Configuration Management
- Deployment
- Lifecycle Management

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-aria-suite-lifecycle-rest-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Site Recovery Manager API

REST API gateway for VMware Site Recovery Manager providing programmatic access to disaster recovery operations including protection groups, recovery plans, and replication management.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-site-recovery-manager-rest-api-gateway/latest/](https://developer.broadcom.com/xapis/vmware-site-recovery-manager-rest-api-gateway/latest/)
- **Base URL:** `https://{{srm-host}}/api`

#### Tags

- Business Continuity
- Disaster Recovery
- Replication
- Site Recovery

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-site-recovery-manager-rest-api-gateway/latest/)
- [Documentation](https://techdocs.broadcom.com/us/en/vmware-cis/live-recovery/site-recovery-manager/8-8/site-recovery-manager-administration-8-8/using-the-site-recovery-manager-rest-api-gateway.html)
- [SDK](https://developer.broadcom.com/sdks/site-recovery-manager-srm/latest)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Live Cyber Recovery API

REST API for VMware Live Cyber Recovery providing access to cloud file systems, protected sites, VMs, protection groups, and recovery plans for ransomware and disaster recovery.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-live-cyber-recovery-api/latest/](https://developer.broadcom.com/xapis/vmware-live-cyber-recovery-api/latest/)
- **Base URL:** `https://{{vcdr-orchestrator}}/api`

#### Tags

- Cloud Recovery
- Cyber Recovery
- Data Protection
- Ransomware Protection

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-live-cyber-recovery-api/latest/)
- [SDK](https://developer.broadcom.com/sdks/vmware-live-cyber-recovery-sdk/latest)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Live Site Recovery API

API for VMware Live Site Recovery providing disaster recovery as a service capabilities with automated recovery plan execution and testing.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-live-site-recovery-v1-api/latest/](https://developer.broadcom.com/xapis/vmware-live-site-recovery-v1-api/latest/)
- **Base URL:** `https://{{vcdr-host}}/api/vcdr/v1`

#### Tags

- Business Continuity
- Disaster Recovery
- DRaaS
- Site Recovery

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-live-site-recovery-v1-api/latest/)
- [Documentation](https://techdocs.broadcom.com/us/en/vmware-cis/live-recovery/live-site-recovery/9-0/how-do-i-protect-my-environment/using-the-site-recovery-manager-rest-api-gateway.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware vDefend API

API for VMware vDefend lateral security platform providing network security segmentation, threat detection, network analysis, and malware prevention capabilities.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-vdefend/latest/](https://developer.broadcom.com/xapis/vmware-vdefend/latest/)
- **Base URL:** `https://{{nsx-manager}}/api/v1`

#### Tags

- Firewall
- Micro-Segmentation
- Network Security
- Threat Detection

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-vdefend/latest/)
- [Documentation](https://techdocs.broadcom.com/us/en/vmware-security-load-balancing/vdefend.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VCF Operations API

API for VMware Cloud Foundation operations management providing monitoring, analytics, and performance optimization for VCF deployments.

- **Human URL:** [https://developer.broadcom.com/xapis/vcf-operations-api/latest/](https://developer.broadcom.com/xapis/vcf-operations-api/latest/)
- **Base URL:** `https://{{vrops-host}}/suite-api/api`

#### Tags

- Analytics
- Cloud Foundation
- Monitoring
- Operations Management

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vcf-operations-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware View API

API providing comprehensive access to VMware Horizon View data structures for managing virtual desktop infrastructure including desktop pools, sessions, and entitlements.

- **Human URL:** [https://developer.broadcom.com/xapis/view-api/latest/](https://developer.broadcom.com/xapis/view-api/latest/)
- **Base URL:** `https://{{horizon-server}}/view-vlsi/rest`

#### Tags

- Desktop Management
- Horizon View
- VDI
- Virtual Desktop

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/view-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Cloud on AWS API Reference

Comprehensive API reference for managing VMware Cloud on AWS infrastructure including SDDCs, organizations, subscriptions, and ESX host configurations.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-cloud-on-aws-api-reference/latest/](https://developer.broadcom.com/xapis/vmware-cloud-on-aws-api-reference/latest/)
- **Base URL:** `https://vmc.vmware.com/vmc/api`

#### Tags

- AWS
- Cloud Infrastructure
- Hybrid Cloud
- SDDC

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-cloud-on-aws-api-reference/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NSX VMC Policy API

API for managing logical networking in NSX for VMware Cloud on AWS customers including security policies, segments, and gateway configurations.

- **Human URL:** [https://developer.broadcom.com/xapis/nsx-vmc-policy/latest/](https://developer.broadcom.com/xapis/nsx-vmc-policy/latest/)
- **Base URL:** `https://{{nsx-manager}}/policy/api/v1`

#### Tags

- AWS
- Network Virtualization
- Security Policy
- VMware Cloud

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/nsx-vmc-policy/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Cloud Disaster Recovery API

REST API for VMware Cloud Disaster Recovery providing access to cloud file systems, protected sites, protected VMs, protection groups, and Recovery SDDCs.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-cloud-disaster-recovery-api-reference/latest/](https://developer.broadcom.com/xapis/vmware-cloud-disaster-recovery-api-reference/latest/)
- **Base URL:** `https://{{vcdr-host}}/api`

#### Tags

- Business Continuity
- Cloud Recovery
- Data Protection
- Disaster Recovery

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-cloud-disaster-recovery-api-reference/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Aria Automation Orchestrator API

REST API for VMware Aria Automation Orchestrator enabling programmatic access to run and schedule workflows, retrieve workflow details and logs, browse inventories and plug-ins, and import and export packages.

- **Human URL:** [https://developer.broadcom.com/xapis/vrealize-orchestrator-api/latest/](https://developer.broadcom.com/xapis/vrealize-orchestrator-api/latest/)
- **Base URL:** `https://{{vro-host}}/vco/api`

#### Tags

- IT Automation
- Orchestration
- Plug-Ins
- Workflow Automation

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vrealize-orchestrator-api/latest/)
- [Documentation](https://techdocs.broadcom.com/us/en/vmware-cis/aria/aria-automation/all/developing-web-services-client-for-vco-all/using-the-orchestrator-rest-api.html)
- [SDK](https://techdocs.broadcom.com/us/en/vmware-cis/aria/aria-automation/all/vro-plug-in-development-all.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Aria Operations for Networks SaaS API

SaaS version of the VMware Aria Operations for Networks API providing cloud-hosted network visibility, analytics, and microsegmentation planning capabilities with token-based authentication.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-aria-operations-for-networks-saas-api/latest/](https://developer.broadcom.com/xapis/vmware-aria-operations-for-networks-saas-api/latest/)
- **Base URL:** `https://{{vrni-saas-host}}/api/ni`

#### Tags

- Microsegmentation
- Network Analytics
- Network Monitoring
- SaaS

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-aria-operations-for-networks-saas-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VCF Operations for Networks API

API for VCF Operations for Networks providing network visibility, analytics, and troubleshooting for VMware Cloud Foundation deployments.

- **Human URL:** [https://developer.broadcom.com/xapis/vcf-operations-for-networks-api/latest/](https://developer.broadcom.com/xapis/vcf-operations-for-networks-api/latest/)
- **Base URL:** `https://{{vrni-host}}/api/ni`

#### Tags

- Cloud Foundation
- Network Analytics
- Network Monitoring
- Troubleshooting

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vcf-operations-for-networks-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Avi Load Balancer API

RESTful API for VMware Avi Load Balancer providing programmatic access to application delivery services including virtual services, pools, service engines, analytics, and health monitoring.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-avi-load-balancer/latest/](https://developer.broadcom.com/xapis/vmware-avi-load-balancer/latest/)
- **Base URL:** `https://{{avi-controller}}/api`

#### Tags

- Analytics
- Application Delivery
- Load Balancing
- Traffic Management

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-avi-load-balancer/latest/)
- [Documentation](https://techdocs.broadcom.com/us/en/vmware-security-load-balancing/avi-load-balancer.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Data Services Manager API

API for VMware Data Services Manager providing on-demand provisioning and automated management of PostgreSQL, MySQL, and Microsoft SQL Server databases in vSphere environments.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-data-services-manager/latest/](https://developer.broadcom.com/xapis/vmware-data-services-manager/latest/)
- **Base URL:** `https://{{dsm-host}}/api`

#### Tags

- Data Services
- Database Management
- MySQL
- PostgreSQL

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-data-services-manager/latest/)
- [Documentation](https://techdocs.broadcom.com/us/en/vmware-cis/dsm/data-services-manager/2-1/access-the-vmware-data-services-manager-api.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Data Services Manager Kubernetes API

Kubernetes API for VMware Data Services Manager enabling self-service consumption of supported data services through Kubernetes custom resources.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-data-services-manager-kubernetes-api/latest/all-api-ref.html](https://developer.broadcom.com/xapis/vmware-data-services-manager-kubernetes-api/latest/all-api-ref.html)
- **Base URL:** `https://{{k8s-api}}/apis`

#### Tags

- Data Services
- Database Management
- Kubernetes
- Self-Service

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-data-services-manager-kubernetes-api/latest/all-api-ref.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### App Volumes API

API for VMware App Volumes providing programmatic access to real-time application delivery and lifecycle management for virtual desktops and published applications.

- **Human URL:** [https://developer.broadcom.com/xapis/app-volumes-api/latest/](https://developer.broadcom.com/xapis/app-volumes-api/latest/)
- **Base URL:** `https://{{app-volumes-manager}}/api`

#### Tags

- Application Delivery
- Application Management
- Desktop Virtualization
- VDI

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/app-volumes-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware vSphere Kubernetes Service API

API for VMware vSphere Kubernetes Service enabling management of Tanzu Kubernetes clusters on vSphere including cluster lifecycle, node pools, and infrastructure configuration.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-vsphere-kubernetes-service/latest/api-docs.html](https://developer.broadcom.com/xapis/vmware-vsphere-kubernetes-service/latest/api-docs.html)
- **Base URL:** `https://{{vcenter}}/api`

#### Tags

- Container Management
- Kubernetes
- Tanzu
- vSphere

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-vsphere-kubernetes-service/latest/api-docs.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SDDC Manager API

API for SDDC Manager providing programmatic access to VMware Cloud Foundation workload domain lifecycle management, host commissioning, and infrastructure configuration.

- **Human URL:** [https://developer.broadcom.com/xapis/sddc-manager-api/latest/](https://developer.broadcom.com/xapis/sddc-manager-api/latest/)
- **Base URL:** `https://{{sddc-manager}}/v1`

#### Tags

- Cloud Foundation
- Infrastructure
- Lifecycle Management
- SDDC

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/sddc-manager-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VCF Installer API

API for VMware Cloud Foundation Installer providing automated infrastructure bringup and initial deployment of VCF components.

- **Human URL:** [https://developer.broadcom.com/xapis/vcf-installer-api/latest/](https://developer.broadcom.com/xapis/vcf-installer-api/latest/)
- **Base URL:** `https://{{cloud-builder}}/v1`

#### Tags

- Automation
- Cloud Foundation
- Deployment
- Installation

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vcf-installer-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VCF Operations Orchestrator API

REST API for VMware Cloud Foundation Operations Orchestrator providing workflow automation and orchestration capabilities for VCF infrastructure management.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-cloud-foundation-operations-orchestrator-api/latest/](https://developer.broadcom.com/xapis/vmware-cloud-foundation-operations-orchestrator-api/latest/)
- **Base URL:** `https://{{vro-host}}/vco/api`

#### Tags

- Cloud Foundation
- Operations
- Orchestration
- Workflow Automation

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-cloud-foundation-operations-orchestrator-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Cloud Director OpenAPI

Modern RESTful API for VMware Cloud Director defined using OpenAPI standards providing cloud service delivery and multi-tenancy management capabilities.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-cloud-director-openapi/latest/](https://developer.broadcom.com/xapis/vmware-cloud-director-openapi/latest/)
- **Base URL:** `https://{{vcd-host}}/cloudapi`

#### Tags

- Cloud Management
- Multi-Tenancy
- OpenAPI
- Service Provider

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-cloud-director-openapi/latest/)
- [Getting Started](https://techdocs.broadcom.com/us/en/vmware-cis/cloud-director/vmware-cloud-director/10-6/getting-started-with-vcloud-openapis-10-6.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Cloud Director API

XML-based API for VMware Cloud Director providing comprehensive cloud service provider capabilities including organization, VDC, vApp, and catalog management.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-cloud-director-api/latest/](https://developer.broadcom.com/xapis/vmware-cloud-director-api/latest/)
- **Base URL:** `https://{{vcd-host}}/api`

#### Tags

- Cloud Management
- Multi-Tenancy
- Service Provider
- XML

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-cloud-director-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Identity Manager API

API for VMware Identity Manager providing identity and access management capabilities including authentication, authorization, directory integration, and single sign-on.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-identity-manager-api/latest/](https://developer.broadcom.com/xapis/vmware-identity-manager-api/latest/)
- **Base URL:** `https://{{idm-host}}/SAAS/jersey/manager/api`

#### Tags

- Access Management
- Authentication
- Identity Management
- Single Sign-On

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-identity-manager-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Operations for Applications REST API

REST API for Operations for Applications providing access to metrics, dashboards, alerts, events, and integrations for full-stack observability and monitoring.

- **Human URL:** [https://developer.broadcom.com/xapis/operations-for-applications-rest-api/latest/](https://developer.broadcom.com/xapis/operations-for-applications-rest-api/latest/)
- **Base URL:** `https://{{wavefront-host}}/api/v2`

#### Tags

- Dashboards
- Metrics
- Monitoring
- Observability

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/operations-for-applications-rest-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Data Management for VMware Tanzu REST API

REST API for Data Management for VMware Tanzu providing database-as-a-service capabilities for provisioning and managing data services on Kubernetes.

- **Human URL:** [https://developer.broadcom.com/xapis/data-management-for-vmware-tanzu-rest-api/latest/](https://developer.broadcom.com/xapis/data-management-for-vmware-tanzu-rest-api/latest/)
- **Base URL:** `https://{{tanzu-data-host}}/api`

#### Tags

- Data Management
- Database
- Kubernetes
- Tanzu

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/data-management-for-vmware-tanzu-rest-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Cloud Foundation for VxRail API

API for managing VMware Cloud Foundation deployments on Dell VxRail hyperconverged infrastructure including cluster expansion, lifecycle management, and VxRail-specific operations.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-cloud-foundation-for-vxrail-api/latest/](https://developer.broadcom.com/xapis/vmware-cloud-foundation-for-vxrail-api/latest/)
- **Base URL:** `https://{{sddc-manager}}/v1`

#### Tags

- Cloud Foundation
- Dell
- Hyperconverged Infrastructure
- VxRail

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-cloud-foundation-for-vxrail-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VCF Usage Meter API

API for VMware Cloud Foundation Usage Meter providing metering and usage reporting capabilities for VMware product consumption tracking by service providers.

- **Human URL:** [https://developer.broadcom.com/xapis/vcf-usage-meter-apis/latest/](https://developer.broadcom.com/xapis/vcf-usage-meter-apis/latest/)
- **Base URL:** `https://{{usage-meter}}/api`

#### Tags

- Billing
- Reporting
- Service Provider
- Usage Metering

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vcf-usage-meter-apis/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Virtual Storage Lifecycle Management API

API for managing the lifecycle of virtual storage including first-class disks, storage policies, and virtual disk operations in vSphere environments.

- **Human URL:** [https://developer.broadcom.com/xapis/virtual-storage-lifecycle-management-api/latest/](https://developer.broadcom.com/xapis/virtual-storage-lifecycle-management-api/latest/)
- **Base URL:** `https://{{vcenter}}/api`

#### Tags

- Lifecycle Management
- Storage
- Storage Policy
- Virtual Disk

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/virtual-storage-lifecycle-management-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Private AI Service API

API for VMware Private AI providing on-premises AI and machine learning infrastructure services for deploying and managing AI workloads within VMware environments.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-private-ai-service-api/latest/](https://developer.broadcom.com/xapis/vmware-private-ai-service-api/latest/)
- **Base URL:** `https://{{pai-host}}/api`

#### Tags

- Artificial Intelligence
- Infrastructure
- Machine Learning
- Private AI

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-private-ai-service-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware HCX API

REST API for VMware HCX enabling workload mobility, network extension, and disaster recovery across data centers and clouds with support for migration automation and service mesh management.

- **Human URL:** [https://techdocs.broadcom.com/us/en/vmware-cis/hcx/vmware-hcx/4-10.html](https://techdocs.broadcom.com/us/en/vmware-cis/hcx/vmware-hcx/4-10.html)
- **Base URL:** `https://{{hcx-manager}}/hybridity/api`

#### Tags

- Disaster Recovery
- Hybrid Cloud
- Network Extension
- Workload Migration

#### Properties

- [Documentation](https://techdocs.broadcom.com/us/en/vmware-cis/hcx/vmware-hcx/4-10.html)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VMware Cloud Provider Lifecycle Manager API

API for managing the lifecycle of VMware cloud provider environments including deployment, upgrade, and configuration of VMware products for service providers.

- **Human URL:** [https://developer.broadcom.com/xapis/vmware-cloud-provider-lifecycle-manager-api/latest/](https://developer.broadcom.com/xapis/vmware-cloud-provider-lifecycle-manager-api/latest/)
- **Base URL:** `https://{{vclm-host}}/api`

#### Tags

- Cloud Provider
- Deployment
- Lifecycle Management
- Service Provider

#### Properties

- [API Reference](https://developer.broadcom.com/xapis/vmware-cloud-provider-lifecycle-manager-api/latest/)
- [Postman Collection](collections/vmware-vsphere-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vmware-vsphere-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vmware)
- [Portal](https://developer.broadcom.com/)
- [Documentation](https://techdocs.broadcom.com/us/en/vmware-cis.html)
- [SDK](https://developer.broadcom.com/vmware-sdk-api)
- [Code Examples](https://developer.broadcom.com/codesample)
- [C L I](https://developer.broadcom.com/powercli/latest/)
- [Blog](https://blogs.vmware.com/code/)
- [Support](https://www.broadcom.com/support/vmware-services)
- [GitHub Organization](https://github.com/vmware)
- [GitHub Repository](https://github.com/vmware-samples)
- [Login](https://developer.broadcom.com/)
- [Privacy Policy](https://www.broadcom.com/company/legal/privacy/policy)
- [Terms of Service](https://www.broadcom.com/company/legal/terms-of-use)
- [Status Page](https://status.vmware-services.io/)
- [Pricing](https://www.broadcom.com/products/software/vmware)
- [JSON-LD](json-ld/vmware-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/vmware-virtual-machine-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/vmware-spectral-rules.yml)
- [Vocabulary](vocabulary/vmware-vocabulary.yaml)
- [Features](https://www.vmware.com/products.html)
- [Use Cases](https://www.vmware.com/solutions.html)
- [Integrations](https://www.vmware.com/partners.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
