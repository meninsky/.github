# Welcome to meninsky

This organization contains repositories that support our projects, clients, and shared infrastructure. Below is an overview of the key categories of repositories within this organization.

## Client Repositories

Client repositories are dedicated to specific clients and are structured to contain all resources related to that client. These repositories follow the naming convention:

```
client-<clientname>-<region>
```

### What to Expect in a Client Repository:

- **ETL Pipelines:** Tools and workflows for data extraction, transformation, and loading.
- **Client-Specific Configurations:** Custom scripts, policies, or data models tailored to the client’s needs.
- **Documentation:** Clear and concise documentation on how to use the resources within the repository.

Example:

- `client-acme-us-west`
- `client-globex-eu-central`

---

## SparkFlow

SparkFlow is a repository designed for executing Spark ETLs. It serves as a foundational framework for scalable and efficient data processing tasks. The repository includes:

- Pre-built templates for common ETL jobs.
- Documentation to help users get started quickly.
- Tools for managing and monitoring Spark jobs.

For more details, visit the [SparkFlow README](https://github.com/your-org/sparkflow#readme).

---

## Shared-Infra

The `shared-infra` repository contains shared resources that are used across multiple projects and clients. It is minimal by design to avoid becoming a utility repository. The structure includes:

- **Database Definitions:** Common schemas and scripts.
- **Infrastructure Code:** Terraform configurations for shared cloud resources.
- **Documentation:** Guidelines and best practices for managing shared resources.

For additional information, see the [Shared-Infra README](https://github.com/your-org/shared-infra#readme).

---

Thank you for exploring our GitHub organization. If you have any questions, feel free to reach out to the maintainers of the respective repositories.
