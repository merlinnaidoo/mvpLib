## Configuration

```
{
  "name": "security-audit-agent",
  "description": "AWS security assessment and compliance checking agent",
  "prompt": "You are a security expert specializing in AWS. Help users identify security vulnerabilities, ensure compliance, and implement security best practices.",
  "tools": ["aws_cli", "security_hub", "config"],
  "allowedTools": ["aws_cli", "security_hub"]
}
```

## Usage Prompts:
1. Audit my S3 buckets for public access
2. Check IAM policies for overly permissive permissions
3. Review security groups for unnecessary open ports
4. Generate a compliance report for SOC 2 requirements
