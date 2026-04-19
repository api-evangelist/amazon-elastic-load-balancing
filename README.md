# Amazon Elastic Load Balancing (amazon-elastic-load-balancing)
Amazon Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions, ensuring high availability and fault tolerance for your applications.

**URL:** [https://aws.amazon.com/elasticloadbalancing/](https://aws.amazon.com/elasticloadbalancing/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon Web Services, AWS, High Availability, Load Balancing, Networking, Scalability

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Elastic Load Balancing v2 API
API for managing Application Load Balancers (ALB), Network Load Balancers (NLB), and Gateway Load Balancers (GLB) with advanced routing and target group management.

**Human URL:** [https://aws.amazon.com/elasticloadbalancing/](https://aws.amazon.com/elasticloadbalancing/)

#### Tags:

 - ALB, GLB, Load Balancing, Networking, NLB

#### Properties

- [Documentation](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/)
- [OpenAPI](openapi/amazon-elastic-load-balancing-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/elasticloadbalancing/latest/APIReference/)
- [GettingStarted](https://aws.amazon.com/elasticloadbalancing/getting-started/)
- [Pricing](https://aws.amazon.com/elasticloadbalancing/pricing/)
- [FAQ](https://aws.amazon.com/elasticloadbalancing/faqs/)
- [JSONSchema](json-schema/amazon-elastic-load-balancing-action-schema.json)
- [JSONSchema](json-schema/amazon-elastic-load-balancing-create-listener-response-schema.json)
- [JSONSchema](json-schema/amazon-elastic-load-balancing-create-load-balancer-response-schema.json)
- [JSONLD](json-ld/amazon-elastic-load-balancing-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/elasticloadbalancing/)
- [Documentation](https://docs.aws.amazon.com/elasticloadbalancing/)
- [Blog](https://aws.amazon.com/blogs/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/ec2/home#LoadBalancers/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/support/)
- [FAQ](https://aws.amazon.com/elasticloadbalancing/faqs/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Compliance](https://aws.amazon.com/compliance/)
- [Security](https://aws.amazon.com/security/)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/elasticloadbalancing)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Application Load Balancer | HTTP/HTTPS load balancing with advanced request routing based on content |
| Network Load Balancer | Ultra-high performance TCP/UDP load balancing at OSI layer 4 |
| Gateway Load Balancer | Distribute traffic to third-party virtual appliances for inspection |
| Health Checks | Automatically route traffic away from unhealthy targets |
| SSL/TLS Termination | Offload SSL/TLS decryption from application servers |

## Use Cases

| Name | Description |
|------|-------------|
| Web Application Load Balancing | Distribute HTTP/HTTPS traffic across multiple web servers |
| Microservices Routing | Route requests to different microservices based on URL paths or headers |
| Container Load Balancing | Load balance traffic to ECS containers and Kubernetes pods |
| Multi-Region Traffic Management | Distribute global traffic across multiple AWS regions |

## Integrations

| Name | Description |
|------|-------------|
| Amazon EC2 | Distribute traffic across EC2 instances |
| Amazon ECS | Load balance traffic to containerized applications |
| AWS Lambda | Route HTTP requests directly to Lambda functions |
| Amazon Route 53 | Integrate with DNS for global traffic routing |
| AWS WAF | Protect applications from web exploits and bots |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-elastic-load-balancing](openapi/amazon-elastic-load-balancing-openapi.yml)

### JSON Schema

- [amazon-elastic-load-balancing-action](json-schema/amazon-elastic-load-balancing-action-schema.json)
- [amazon-elastic-load-balancing-create-listener-response](json-schema/amazon-elastic-load-balancing-create-listener-response-schema.json)
- [amazon-elastic-load-balancing-create-load-balancer-response](json-schema/amazon-elastic-load-balancing-create-load-balancer-response-schema.json)
- [amazon-elastic-load-balancing-create-rule-response](json-schema/amazon-elastic-load-balancing-create-rule-response-schema.json)
- [amazon-elastic-load-balancing-create-target-group-response](json-schema/amazon-elastic-load-balancing-create-target-group-response-schema.json)
- [amazon-elastic-load-balancing-describe-listeners-response](json-schema/amazon-elastic-load-balancing-describe-listeners-response-schema.json)
- [amazon-elastic-load-balancing-describe-load-balancers-response](json-schema/amazon-elastic-load-balancing-describe-load-balancers-response-schema.json)
- [amazon-elastic-load-balancing-describe-rules-response](json-schema/amazon-elastic-load-balancing-describe-rules-response-schema.json)
- [amazon-elastic-load-balancing-describe-target-groups-response](json-schema/amazon-elastic-load-balancing-describe-target-groups-response-schema.json)
- [amazon-elastic-load-balancing-describe-target-health-response](json-schema/amazon-elastic-load-balancing-describe-target-health-response-schema.json)
- *...and 6 more*

### JSON Structure

- [amazon-elastic-load-balancing-action](json-structure/amazon-elastic-load-balancing-action-structure.json)
- [amazon-elastic-load-balancing-create-listener-response](json-structure/amazon-elastic-load-balancing-create-listener-response-structure.json)
- [amazon-elastic-load-balancing-create-load-balancer-response](json-structure/amazon-elastic-load-balancing-create-load-balancer-response-structure.json)
- [amazon-elastic-load-balancing-create-rule-response](json-structure/amazon-elastic-load-balancing-create-rule-response-structure.json)
- [amazon-elastic-load-balancing-create-target-group-response](json-structure/amazon-elastic-load-balancing-create-target-group-response-structure.json)
- [amazon-elastic-load-balancing-describe-listeners-response](json-structure/amazon-elastic-load-balancing-describe-listeners-response-structure.json)
- [amazon-elastic-load-balancing-describe-load-balancers-response](json-structure/amazon-elastic-load-balancing-describe-load-balancers-response-structure.json)
- [amazon-elastic-load-balancing-describe-rules-response](json-structure/amazon-elastic-load-balancing-describe-rules-response-structure.json)
- [amazon-elastic-load-balancing-describe-target-groups-response](json-structure/amazon-elastic-load-balancing-describe-target-groups-response-structure.json)
- [amazon-elastic-load-balancing-describe-target-health-response](json-structure/amazon-elastic-load-balancing-describe-target-health-response-structure.json)
- *...and 6 more*

### JSON-LD

- [amazon-elastic-load-balancing](json-ld/amazon-elastic-load-balancing-context.jsonld)

### Examples

- [amazon-elastic-load-balancing-action](examples/amazon-elastic-load-balancing-action-example.json)
- [amazon-elastic-load-balancing-create-listener-response](examples/amazon-elastic-load-balancing-create-listener-response-example.json)
- [amazon-elastic-load-balancing-create-load-balancer-response](examples/amazon-elastic-load-balancing-create-load-balancer-response-example.json)
- [amazon-elastic-load-balancing-create-rule-response](examples/amazon-elastic-load-balancing-create-rule-response-example.json)
- [amazon-elastic-load-balancing-create-target-group-response](examples/amazon-elastic-load-balancing-create-target-group-response-example.json)
- [amazon-elastic-load-balancing-describe-listeners-response](examples/amazon-elastic-load-balancing-describe-listeners-response-example.json)
- [amazon-elastic-load-balancing-describe-load-balancers-response](examples/amazon-elastic-load-balancing-describe-load-balancers-response-example.json)
- [amazon-elastic-load-balancing-describe-rules-response](examples/amazon-elastic-load-balancing-describe-rules-response-example.json)
- [amazon-elastic-load-balancing-describe-target-groups-response](examples/amazon-elastic-load-balancing-describe-target-groups-response-example.json)
- [amazon-elastic-load-balancing-describe-target-health-response](examples/amazon-elastic-load-balancing-describe-target-health-response-example.json)
- *...and 6 more*

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [ELB](capabilities/shared/api.yaml) — 13 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Amazon Elastic Load Balancing Management](capabilities/amazon-elastic-load-balancing-capability.yaml) | 13 | Cloud Architect |

## Vocabulary

- [Amazon Elastic Load Balancing Vocabulary](vocabulary/amazon-elastic-load-balancing-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 6 actions, 1 workflows, and 2 personas

## Rules

- [amazon-elastic-load-balancing-spectral-rules.yml](rules/amazon-elastic-load-balancing-spectral-rules.yml) — 0 rules enforcing Amazon Elastic Load Balancing API conventions

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
