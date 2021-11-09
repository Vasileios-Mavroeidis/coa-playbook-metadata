# coa-playbook-metadata-template


| Element | Description |
| :--- | :--- |
| **id** | A value that uniquely identifies the playbook. |
| **created** | The time at which the playbook was originally created. |
| **modified** | The time that this particular version of the playbook was last modified. |
| **revoked** | A boolean that identifies if the playbook creator deems that this playbook is no longer valid. |
| **creator** | The entity that created this playbook. It can be, for example, a natural person or an organization. It may be represented using an id that identifies the creator. |
| **valid_from** | The time from which the playbook is considered valid and the steps that it contains can be executed. |
| **valid_until** | The time at which this playbook should no longer be considered a valid playbook to be executed. |
| **description** | An explanation, details, and more context about what this playbook does and tries to accomplish. |
| **label** | An optional set of terms, labels, or tags associated with this playbook (e.g., aliases of adversary groups or malware family/variant/name that this playbook is related to). |
| **impact** | From 0 to 100, an integer representing the impact the playbook has on the organization. A value of 0 means specifically undefined. Values range from 1, the lowest impact, to a value of 100, the highest. For example, a purely investigative playbook that is non-invasive would have a low impact value of 1. In contrast, a playbook that performs changes such as adding rules into a firewall would have a higher impact value. |
| **severity** | From 0 to 100, an integer representing the seriousness of the conditions that this playbook addresses. A value of 0 means specifically undefined. Values range from 1, the lowest severity, to a value of 100, the highest. |
| **priority** | From 0 to 100, an integer representing the priority of this playbook relative to other defined playbooks. A value of 0 means specifically undefined. Values range from 1, the highest priority, to a value of 100, the lowest. |
| **organization_type** | The type of organization that the playbook is intended for. This can be an industry sector. |







