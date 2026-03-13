# Amazon Elastic Load Balancing API

Amazon Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions, ensuring high availability and fault tolerance for your applications.

## APIs

- **Elastic Load Balancing v2 API** - API for managing Application Load Balancers (ALB), Network Load Balancers (NLB), and Gateway Load Balancers (GLB). Provides advanced routing, target group management, listener configuration, and rule-based traffic distribution across multiple targets.
- **Classic Load Balancing API** - API for managing Classic Load Balancers, which provide basic load balancing across multiple Amazon EC2 instances at the request level and the connection level. Classic Load Balancers are intended for applications built within the EC2-Classic network.

## Resources

### Documentation

- [Documentation](https://docs.aws.amazon.com/elasticloadbalancing/latest/APIReference/)
- [User Guide](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/)
- [API Reference](https://docs.aws.amazon.com/elasticloadbalancing/latest/APIReference/)
- [CLI Reference (v2)](https://docs.aws.amazon.com/cli/latest/reference/elbv2/)
- [CLI Reference (Classic)](https://docs.aws.amazon.com/cli/latest/reference/elb/)
- [Getting Started](https://aws.amazon.com/elasticloadbalancing/getting-started/)

### Specifications

- [OpenAPI](openapi/amazon-elastic-load-balancing-openapi.yml)
- [JSON Schema](json-schema/amazon-elastic-load-balancing-schema.json)
- [JSON-LD](json-ld/amazon-elastic-load-balancing-context.jsonld)

### General

- [Pricing](https://aws.amazon.com/elasticloadbalancing/pricing/)
- [FAQ](https://aws.amazon.com/elasticloadbalancing/faqs/)
- [Security](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/security.html)

## Maintainers

- Kin Lane - kin@apievangelist.com
