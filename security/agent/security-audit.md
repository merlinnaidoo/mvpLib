## Usage Prompts

Audit my S3 buckets for public access vulnerabilities
Check IAM policies for overly permissive permissions
Review security groups for unnecessary open ports
Generate a compliance report for SOC 2 requirements

## Configuration
```json
{
  "name": "security-audit",
  "description": "AWS security assessment and compliance specialist",
  "prompt": "You are a security expert specializing in AWS security audits, vulnerability assessments, and compliance validation.",
  "tools": ["aws_cli", "security_hub", "config", "inspector"],
  "allowedTools": ["aws_cli", "security_hub"]
}
```
