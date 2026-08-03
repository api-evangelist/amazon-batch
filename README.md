# Amazon Batch

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

AWS Batch enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS. AWS Batch dynamically provisions the optimal quantity and type of compute resources based on the volume and specific resource requirements of the batch jobs submitted.

**Human URL:** [https://aws.amazon.com/batch/](https://aws.amazon.com/batch/)

**API Reference:** [https://docs.aws.amazon.com/batch/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/batch/latest/APIReference/Welcome.html)

## APIs

### Amazon Batch API

Programmatic management of batch computing workloads including compute environments, job queues, job definitions, scheduling policies, and batch job submission and monitoring.

**Base URL:** `https://batch.amazonaws.com`

#### Key Operations

| Operation | Description |
|---|---|
| CreateComputeEnvironment | Create managed or unmanaged compute resources |
| CreateJobQueue | Create a queue for routing jobs to compute environments |
| RegisterJobDefinition | Register a versioned job template |
| SubmitJob | Submit a batch job (single, array, or multi-node) |
| DescribeJobs | Monitor job status and details |
| TerminateJob | Cancel or terminate a running job |
| CreateSchedulingPolicy | Configure fair-share scheduling |

## Features

- **Managed Compute Environments** — Auto-provision EC2, Fargate, or EKS resources based on demand
- **Array Jobs** — Run N parallel job instances for parameter sweeps and data parallelism
- **Multi-Node Parallel Jobs** — Tightly-coupled HPC workloads across multiple EC2 instances
- **Spot Instance Integration** — Reduce costs by up to 90% with automatic Spot retry on interruption
- **Fair-Share Scheduling** — Equitable resource distribution across users and teams
- **GPU Support** — GPU-accelerated ML training and scientific simulations
- **EKS Integration** — Run batch jobs on Amazon EKS with Kubernetes pod specifications

## Use Cases

- **Scientific Computing** — Genomics, climate modeling, and large-scale simulations
- **Data Processing Pipelines** — Parallel ETL and analytics with Spot Instances
- **Machine Learning Training** — Distributed GPU training with multi-node parallel jobs
- **Media Transcoding** — High-volume parallel media processing

## Artifacts

| Type | URL |
|---|---|
| OpenAPI Spec | [openapi/amazon-batch-openapi.yml](openapi/amazon-batch-openapi.yml) |
| OpenAPI (APIs.guru) | [https://api.apis.guru/v2/specs/amazonaws.com/batch/2016-08-10/openapi.json](https://api.apis.guru/v2/specs/amazonaws.com/batch/2016-08-10/openapi.json) |
| JSON Schema | [json-schema/amazon-batch-schema.json](json-schema/amazon-batch-schema.json) |
| JSON Structure | [json-structure/batch-resource-structure.json](json-structure/batch-resource-structure.json) |
| JSON-LD Context | [json-ld/amazon-batch-context.jsonld](json-ld/amazon-batch-context.jsonld) |
| Spectral Ruleset | [spectral/ruleset.yml](spectral/ruleset.yml) |
| Capabilities | [capabilities/capabilities.yml](capabilities/capabilities.yml) |
| Vocabulary | [vocabulary/vocabulary.yml](vocabulary/vocabulary.yml) |
| Examples | [examples/](examples/) |

## Common Properties

| Type | URL |
|---|---|
| Documentation | [https://docs.aws.amazon.com/batch/latest/userguide/what-is-batch.html](https://docs.aws.amazon.com/batch/latest/userguide/what-is-batch.html) |
| API Reference | [https://docs.aws.amazon.com/batch/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/batch/latest/APIReference/Welcome.html) |
| CLI Reference | [https://docs.aws.amazon.com/cli/latest/reference/batch/](https://docs.aws.amazon.com/cli/latest/reference/batch/) |
| Pricing | [https://aws.amazon.com/batch/pricing/](https://aws.amazon.com/batch/pricing/) |
| Blog | [https://aws.amazon.com/blogs/hpc/category/compute/aws-batch/](https://aws.amazon.com/blogs/hpc/category/compute/aws-batch/) |
| Stack Overflow | [https://stackoverflow.com/questions/tagged/aws-batch](https://stackoverflow.com/questions/tagged/aws-batch) |

## Maintainers

**Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
