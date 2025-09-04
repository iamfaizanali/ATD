hello world
Platform Infrastructure Administration
	•	Provisioning and managing Azure VMs hosting Dataiku nodes (Design, Automation, Govern, Deployer).
	•	Configuring VM sizing, scaling strategy, and storage based on workload requirements.
	•	Managing OS-level configurations (Linux kernel tuning, packages, security patches).
	•	Monitoring CPU, memory, disk, and network utilization to prevent resource bottlenecks.
	•	Setting up and managing HA/DR strategy for business continuity.

⸻

2. Dataiku Node Administration
	•	Installation, upgrades, and patching of Dataiku software across environments.
	•	Configuring and maintaining DSS nodes (Design, Automation, Deployer, Govern).
	•	Managing plugins, code environments (Python, R), and libraries for business use cases.
	•	Troubleshooting node issues (JVM, logs, out-of-memory, service restarts).

⸻

3. User & Security Management
	•	Onboarding and managing users, groups, and roles within Dataiku.
	•	Enforcing RBAC, LDAP/SSO integration, and Azure AD authentication.
	•	Managing permissions and project-level access controls.
	•	Implementing Key Vault integration for secret management.

⸻

4. Connectivity & Integrations
	•	Configuring and maintaining connections to data sources (Azure Data Lake, Blob Storage, SQL DBs, Synapse, Databricks, Kafka, etc.).
	•	Ensuring secure integration with Azure Key Vault, Service Principals, Managed Identities.
	•	Setting up API endpoints and webhooks for automation/integration.
	•	Supporting Git/GitLab integration for version control and CI/CD.

⸻

5. Monitoring & Observability
	•	Setting up monitoring dashboards (Azure Monitor, Grafana, Prometheus).
	•	Implementing alerting mechanisms for resource usage, job failures, and platform errors.
	•	Regular review of Dataiku logs (backend, job execution, audit logs).
	•	Managing Splunk / SIEM integration for security and compliance.

⸻

6. Job & Resource Management
	•	Supporting schedulers, scenarios, and automation for pipelines.
	•	Managing Kubernetes/AKS executors (if configured for scaling workloads).
	•	Configuring Spark integration with Databricks/Synapse for heavy workloads.
	•	Handling queue management, parallelism, and execution tuning.

⸻

7. Backup, Recovery & Upgrades
	•	Implementing backup policies for projects, configurations, and metadata.
	•	Performing disaster recovery drills to ensure business continuity.
	•	Planning and executing version upgrades with rollback strategy.
	•	Ensuring compatibility testing for plugins and code environments post-upgrade.

⸻

8. Compliance & Audit
	•	Maintaining audit logs for user actions and job runs.
	•	Supporting compliance requirements (GDPR, internal security policies).
	•	Conducting regular access reviews for users and service accounts.

⸻

9. Incident & Problem Management
	•	Troubleshooting platform issues (failed jobs, connectivity issues, node crashes).
	•	Engaging with Dataiku support/vendor when escalation is needed.
	•	Root cause analysis (RCA) for major incidents.
	•	Maintaining runbooks and knowledge base articles in Confluence.

⸻

10. Cost & Performance Optimization
	•	Monitoring Azure costs for VM usage, storage, and networking.
	•	Implementing auto-shutdown/start policies for cost savings.
	•	Optimizing Spark and Dataiku jobs to reduce compute costs.
	•	Reviewing long-running scenarios and tuning resource allocation.

⸻

11. Documentation & Best Practices
	•	Maintaining Confluence documentation (architecture, runbooks, SOPs).
	•	Publishing how-to guides for users (connecting to data sources, job scheduling, etc.).
	•	Creating knowledge base articles for common issues.
	•	Defining governance and naming standards for projects, datasets, and scenarios.