# Puppet (puppet)

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
