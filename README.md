# F5 Networks (f5-networks)

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

F5 Networks is a leader in application delivery networking technology that specializes in application availability, acceleration, and security solutions.

**APIs.json:** [https://www.f5.com/apis](https://www.f5.com/apis)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- API Gateway
- Application Delivery
- Automation
- Edge Computing
- Kubernetes
- Load Balancing
- Multi-Cloud
- NGINX
- Security
- WAF

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### F5 BIG-IP iControl REST API

The iControl REST API provides programmatic access to manage and configure F5 BIG-IP devices. Enables automation of network, security, and application delivery services.

- **Human URL:** [https://www.f5.com/services/resources/api](https://www.f5.com/services/resources/api)
- **Base URL:** `https://{{bigip_host}}/mgmt/tm`

#### Tags

- ADC
- Application Delivery
- Load Balancing
- Network Management
- Security

#### Properties

- [Documentation](https://clouddocs.f5.com/api/icontrol-rest/)
- [OpenAPI](openapi/bigip-icontrol-rest.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://clouddocs.f5.com/api/icontrol-rest/APIRef_tm_ltm.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/f5-virtual-server-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/f5-networks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/bigip-icontrol-rest-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://clouddocs.f5.com/api/icontrol-rest/Authentication.html)
- [API Reference](https://clouddocs.f5.com/api/icontrol-rest/APIRef.html)
- [Getting Started](https://clouddocs.f5.com/api/)
- [SDK](https://github.com/F5Networks/f5-icontrol-rest-python)
- [SDK](https://f5-sdk.readthedocs.io/)

### F5 Distributed Cloud API

API for F5 Distributed Cloud Services providing multi-cloud networking, application security, and edge computing capabilities.

- **Human URL:** [https://docs.cloud.f5.com/docs/api](https://docs.cloud.f5.com/docs/api)
- **Base URL:** `https://{{tenant}}.console.ves.volterra.io/api`

#### Tags

- API Security
- CDN
- Edge Computing
- Multi-Cloud
- WAF

#### Properties

- [Documentation](https://docs.cloud.f5.com/docs/api)
- [OpenAPI](https://docs.cloud.f5.com/docs/api/swagger) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Console](https://console.ves.volterra.io/)
- [Getting Started](https://docs.cloud.f5.com/docs/how-to/api-how-to)
- [API Reference](https://docs.cloud.f5.com/docs-v2/reference/api-ref)
- [Authentication](https://docs.cloud.f5.com/docs-v2/api/authentication)
- [Changelog](https://docs.cloud.f5.com/docs-v2/platform/changelogs/saas-release-notes)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### F5 NGINX Management Suite API

REST API for managing NGINX instances, monitoring performance, and configuring application delivery through NGINX Management Suite.

- **Human URL:** [https://docs.nginx.com/nginx-management-suite/](https://docs.nginx.com/nginx-management-suite/)
- **Base URL:** `https://{{nms-host}}/api`

#### Tags

- API Gateway
- Application Delivery
- Configuration Management
- Monitoring
- NGINX

#### Properties

- [Documentation](https://docs.nginx.com/nginx-management-suite/admin-guides/api/)
- [API Reference](https://docs.nginx.com/nginx-management-suite/api-reference/)
- [Getting Started](https://docs.nginx.com/nginx-management-suite/getting-started/)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### F5 Essential App Protect API

API for managing F5's application security services including WAF policies, bot defense, and API protection.

- **Human URL:** [https://docs.f5.com/en-us/app-protect](https://docs.f5.com/en-us/app-protect)
- **Base URL:** `https://api.f5.com/app-protect`

#### Tags

- API Protection
- Bot Defense
- DDoS Protection
- Security
- WAF

#### Properties

- [Documentation](https://docs.f5.com/en-us/app-protect/api-reference)
- [Security](https://docs.f5.com/en-us/app-protect/security-policies)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### F5 BIG-IQ Centralized Management API

REST API for BIG-IQ Centralized Management providing programmatic control over BIG-IP device management, licensing, monitoring, and analytics across your F5 infrastructure.

- **Human URL:** [https://clouddocs.f5.com/products/big-iq/mgmt-api/v0.0/](https://clouddocs.f5.com/products/big-iq/mgmt-api/v0.0/)
- **Base URL:** `https://{{bigiq_host}}/mgmt`

#### Tags

- Analytics
- Centralized Management
- Device Management
- Licensing
- Monitoring

#### Properties

- [Documentation](https://clouddocs.f5.com/products/big-iq/mgmt-api/v0.0/)
- [API Reference](https://clouddocs.f5.com/products/big-iq/mgmt-api/v0.0/ApiReferences/bigiq_public_api_ref/r_public_api_references.html)
- [Getting Started](https://clouddocs.f5.com/products/big-iq/mgmt-api/v0.0/HowToSamples/bigiq_public_api_wf/t_bigiq_public_api_workflows.html)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### F5 BIG-IP Application Services 3 Extension API

Declarative API for automating layer 4-7 application services on BIG-IP using JSON declarations. AS3 enables infrastructure-as-code for application delivery configuration.

- **Human URL:** [https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/](https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/)
- **Base URL:** `https://{{bigip_host}}/mgmt/shared/appsvcs`

#### Tags

- Application Delivery
- Application Services
- Automation
- Declarative
- Infrastructure as Code

#### Properties

- [Documentation](https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/)
- [API Reference](https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/refguide/as3-api.html)
- [Getting Started](https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/userguide/)
- [GitHub Repository](https://github.com/F5Networks/f5-appsvcs-extension)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### F5 Declarative Onboarding API

Declarative API for automating layer 1-3 BIG-IP onboarding and initial device configuration using JSON declarations, making BIG-IP available on the network and ready for application services.

- **Human URL:** [https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/](https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/)
- **Base URL:** `https://{{bigip_host}}/mgmt/shared/declarative-onboarding`

#### Tags

- Automation
- Declarative
- Device Configuration
- Infrastructure as Code
- Onboarding

#### Properties

- [Documentation](https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/)
- [API Reference](https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/apidocs.html)
- [Getting Started](https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/using-do.html)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### F5 Telemetry Streaming API

Declarative API for aggregating, normalizing, and forwarding BIG-IP statistics and events to third-party analytics consumers including Splunk, Azure Log Analytics, AWS CloudWatch, and more.

- **Human URL:** [https://clouddocs.f5.com/products/extensions/f5-telemetry-streaming/latest/](https://clouddocs.f5.com/products/extensions/f5-telemetry-streaming/latest/)
- **Base URL:** `https://{{bigip_host}}/mgmt/shared/telemetry`

#### Tags

- Analytics
- Monitoring
- Observability
- Streaming
- Telemetry

#### Properties

- [Documentation](https://clouddocs.f5.com/products/extensions/f5-telemetry-streaming/latest/)
- [API Reference](https://clouddocs.f5.com/products/extensions/f5-telemetry-streaming/latest/rest-api-endpoints.html)
- [GitHub Repository](https://github.com/F5Networks/f5-telemetry-streaming)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### F5 NGINX Plus API

REST API for NGINX Plus providing real-time live activity monitoring, dynamic upstream configuration, key-value store management, and server health statistics without requiring configuration reloads.

- **Human URL:** [https://docs.nginx.com/nginx/](https://docs.nginx.com/nginx/)
- **Base URL:** `https://{{nginx_host}}/api`

#### Tags

- Dynamic Configuration
- Load Balancing
- Monitoring
- NGINX
- Reverse Proxy

#### Properties

- [Documentation](https://docs.nginx.com/nginx/)
- [API Reference](https://docs.nginx.com/nginx/admin-guide/monitoring/live-activity-monitoring/)
- [Getting Started](https://docs.nginx.com/nginx/admin-guide/load-balancer/dynamic-configuration-api/)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### F5 NGINX One Console API

API for managing and monitoring NGINX instances across environments from a single console, including configuration management, performance metrics, security vulnerability tracking, and SSL certificate management.

- **Human URL:** [https://docs.nginx.com/nginx-one-console/](https://docs.nginx.com/nginx-one-console/)
- **Base URL:** `https://{{nginx-one-host}}/api`

#### Tags

- Configuration Management
- Fleet Management
- Monitoring
- NGINX
- Security

#### Properties

- [Documentation](https://docs.nginx.com/nginx-one-console/)
- [API Reference](https://docs.nginx.com/nginx-one-console/api/api-reference-guide/)
- [Authentication](https://docs.nginx.com/nginx-one-console/api/authentication/)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### F5 NGINX Ingress Controller API

Kubernetes Ingress Controller implementation for NGINX and NGINX Plus providing load balancing, SSL/TLS termination, content-based routing, and advanced traffic management for containerized applications.

- **Human URL:** [https://docs.nginx.com/nginx-ingress-controller/](https://docs.nginx.com/nginx-ingress-controller/)
- **Base URL:** `https://{{kubernetes_host}}`

#### Tags

- Containers
- Ingress Controller
- Kubernetes
- Load Balancing
- NGINX

#### Properties

- [Documentation](https://docs.nginx.com/nginx-ingress-controller/)
- [GitHub Repository](https://github.com/nginx/kubernetes-ingress)
- [Postman Collection](collections/bigip-icontrol-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bigip-icontrol-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://docs.nginx.com/)
- [Developer Portal](https://clouddocs.f5.com/)
- [Blog](https://www.f5.com/company/blog)
- [GitHub Organization](https://github.com/F5Networks)
- [GitHub Organization](https://github.com/f5devcentral/)
- [Support](https://support.f5.com/)
- [Status Page](https://www.f5cloudstatus.com/)
- [Terms of Service](https://www.f5.com/company/policies/terms-of-use)
- [Privacy Policy](https://www.f5.com/company/policies/privacy-notice)
- [Sign Up](https://account.f5.com/myf5)
- [Login](https://identity.account.f5.com/)
- [LinkedIn](https://www.linkedin.com/company/f5)
- [X (Twitter)](https://twitter.com/f5networks)
- [YouTube](https://www.f5.com/resources/videos)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
