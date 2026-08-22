# Puppet (puppet)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Puppet provides infrastructure automation and configuration management for hybrid and cloud environments. Puppet Enterprise exposes a collection of service APIs (Orchestrator, RBAC, Node Classifier, Code Manager, Activity, Status, Inventory, Value) that enable programmatic management of nodes, users, classifications, code deployments, and operational events.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/puppet/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/puppet/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Automation
- Configuration Management
- DevOps
- Enterprise
- Infrastructure as Code
- Orchestration
- RBAC

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-04-28

## APIs

### Puppet Enterprise Orchestrator API

The Orchestrator API enables you to gather details about orchestrator jobs you run and inspect application instances. It powers running tasks and orchestration workflows across PE-managed nodes.

- **Human URL:** [https://help.puppet.com/pe/2025.10/topics/orchestrator_api.htm](https://help.puppet.com/pe/2025.10/topics/orchestrator_api.htm)

#### Tags

- Orchestration
- Tasks

#### Properties

- [Documentation](https://help.puppet.com/pe/2025.10/topics/orchestrator_api.htm)
- [Postman Collection](collections/puppet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/puppet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Puppet Enterprise RBAC Service API

The RBAC Service API manages access to PE, generates authentication tokens, and provides user, role, group, and permission management. v2 adds user retrieval with filters, token revocation, and LDAP admin.

- **Human URL:** [https://help.puppet.com/pe/2025.10/topics/rbac_service_api_v1.htm](https://help.puppet.com/pe/2025.10/topics/rbac_service_api_v1.htm)

#### Tags

- RBAC
- Authentication
- Users

#### Properties

- [Documentation](https://help.puppet.com/pe/2025.10/topics/rbac_service_api_v1.htm)
- [Documentation](https://help.puppet.com/pe/2025.10/topics/rbac_service_api_v2.htm)
- [Postman Collection](collections/puppet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/puppet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Puppet Enterprise Node Classifier Service API

The Node Classifier API enables querying node group matches, assigned classes and parameters, and environment assignments. Used to manage how nodes are classified and configured.

- **Human URL:** [https://help.puppet.com/pe/2025.10/topics/classifier_api.htm](https://help.puppet.com/pe/2025.10/topics/classifier_api.htm)

#### Tags

- Classification
- Nodes

#### Properties

- [Documentation](https://help.puppet.com/pe/2025.10/topics/classifier_api.htm)
- [Postman Collection](collections/puppet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/puppet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Puppet Enterprise Code Manager API

The Code Manager API supports webhook creation, deployment queueing, and status monitoring for Puppet code, enabling Git-driven control of Puppet environments.

- **Human URL:** [https://help.puppet.com/pe/2025.10/topics/code_mgr_api.htm](https://help.puppet.com/pe/2025.10/topics/code_mgr_api.htm)

#### Tags

- Code
- Deployment
- Webhooks

#### Properties

- [Documentation](https://help.puppet.com/pe/2025.10/topics/code_mgr_api.htm)
- [Postman Collection](collections/puppet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/puppet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Puppet Enterprise Activity Service API

The Activity Service API queries PE service and user events logged by the activity service, supporting audit and operational visibility.

- **Human URL:** [https://help.puppet.com/pe/2025.10/topics/activity_api.htm](https://help.puppet.com/pe/2025.10/topics/activity_api.htm)

#### Tags

- Activity
- Audit

#### Properties

- [Documentation](https://help.puppet.com/pe/2025.10/topics/activity_api.htm)
- [Postman Collection](collections/puppet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/puppet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Puppet Enterprise Status API

The Status API checks the health status of PE services.

- **Human URL:** [https://help.puppet.com/pe/2025.10/topics/status_api.htm](https://help.puppet.com/pe/2025.10/topics/status_api.htm)

#### Tags

- Health
- Monitoring

#### Properties

- [Documentation](https://help.puppet.com/pe/2025.10/topics/status_api.htm)
- [Postman Collection](collections/puppet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/puppet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Puppet Enterprise Node Inventory API

The Node Inventory API manages inventory service database operations including connection entries and listings.

- **Human URL:** [https://help.puppet.com/pe/2025.10/topics/inventory_api.htm](https://help.puppet.com/pe/2025.10/topics/inventory_api.htm)

#### Tags

- Inventory
- Nodes

#### Properties

- [Documentation](https://help.puppet.com/pe/2025.10/topics/inventory_api.htm)
- [Postman Collection](collections/puppet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/puppet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Puppet Enterprise Value API

The Value API generates automation impact reports on time and cost savings.

- **Human URL:** [https://help.puppet.com/pe/2025.10/topics/value_api.htm](https://help.puppet.com/pe/2025.10/topics/value_api.htm)

#### Tags

- Reports
- Analytics

#### Properties

- [Documentation](https://help.puppet.com/pe/2025.10/topics/value_api.htm)
- [Postman Collection](collections/puppet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/puppet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Puppet Forge

Puppet Forge is the public module repository providing thousands of downloadable Puppet modules.

- **Human URL:** [https://forge.puppet.com/](https://forge.puppet.com/)

#### Tags

- Modules
- Registry

#### Properties

- [Website](https://forge.puppet.com/)
- [Postman Collection](collections/puppet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/puppet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/puppet)
- [Website](https://www.puppet.com/)
- [Documentation](https://help.puppet.com/)
- [Blog](https://www.puppet.com/blog)
- [GitHub Organization](https://github.com/puppetlabs)
- [Forge](https://forge.puppet.com/)
- [Status Page](https://status.puppet.com/)
- [Support](https://support.puppet.com/)
- [Pricing](https://www.puppet.com/pricing)
- [Integrations](https://www.puppet.com/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
