Usage Prompts:
Audit my S3 buckets for public access vulnerabilities
Check IAM policies for overly permissive permissions
Review security groups for unnecessary open ports
Generate a compliance report for SOC 2 requirements

Configuration
{
  "name": "security-audit",
  "description": "AWS security assessment and compliance checking specialist",
  "prompt": "You are a security expert specializing in AWS. Help users identify security vulnerabilities, ensure compliance, and implement security best practices.",
  "tools": ["aws_cli", "security_hub", "config"],
  "allowedTools": ["aws_cli", "security_hub"]
}
