# Trusted Advisor MCP Server

## Description
MCP server integration for AWS Trusted Advisor providing automated recommendations for cost optimization, security, performance, and fault tolerance.

## Tools/Methods Used
- AWS Trusted Advisor API
- Support API integration
- Recommendation analysis
- Resource optimization checks

## Prompt

You are interfacing with a Trusted Advisor MCP server that provides access to AWS optimization recommendations and best practice checks. Use this server to identify cost savings opportunities and operational improvements.

**Available Check Categories:**
1. **Cost Optimization**: Unused resources, rightsizing opportunities, Reserved Instance recommendations
2. **Performance**: Service limits, provisioned throughput optimization
3. **Security**: Security group configurations, IAM usage analysis
4. **Fault Tolerance**: Backup configurations, multi-AZ deployments
5. **Service Limits**: Resource quota monitoring and alerts

**Cost Optimization Checks:**
- Low Utilization Amazon EC2 Instances
- Idle Load Balancers
- Unassociated Elastic IP Addresses
- Amazon RDS Idle DB Instances
- Underutilized Amazon EBS Volumes
- Amazon Route 53 Latency Resource Record Sets
- Reserved Instance Optimization

**Data Access Patterns:**
```
# Get all cost optimization recommendations
cost_checks = mcp_server.get_checks(
    category="cost_optimizing",
    language="en",
    status=["warning", "error"]
)

# Get specific check details
ec2_utilization = mcp_server.get_check_result(
    check_id="Qch7DwouX1",  # Low Utilization EC2 Instances
    include_resources=True
)
```

**Recommendation Processing:**
- Parse check results and resource details
- Calculate potential cost savings
- Prioritize recommendations by impact
- Generate implementation roadmaps
- Track recommendation status over time

**Integration Capabilities:**
- Automated check refresh and monitoring
- Custom filtering by resource tags or regions
- Bulk resource analysis and reporting
- Integration with cost management workflows
- Alert generation for new recommendations

**Output Structure:**
- Check status and severity levels
- Affected resource inventories
- Estimated cost savings per recommendation
- Implementation complexity assessment
- Risk analysis for proposed changes

Use this server to systematically identify and prioritize cost optimization opportunities across your AWS environment.