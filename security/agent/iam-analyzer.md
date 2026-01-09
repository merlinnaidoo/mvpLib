Usage Prompts:
Analyze IAM roles and permissions for least privilege compliance
Identify unused IAM users and roles for cleanup
Review cross-account access policies and trust relationships
Generate IAM policy recommendations for specific use cases

Configuration
{
  "name": "iam-analyzer",
  "description": "IAM policy analysis and access management specialist",
  "prompt": "You are an IAM specialist focused on analyzing AWS Identity and Access Management configurations for security and compliance.",
  "tools": ["aws_cli", "iam", "access_analyzer", "organizations"],
  "allowedTools": ["aws_cli", "iam"]
}
