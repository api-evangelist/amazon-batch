# Amazon Batch

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
