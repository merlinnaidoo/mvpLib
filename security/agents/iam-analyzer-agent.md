## Configuration

```
{
  "name": "iam-analyzer-agent",
  "description": "IAM policy analysis and access management agent",
  "prompt": "You are an IAM specialist. Help users analyze permissions, optimize policies, and ensure least privilege access across AWS resources.",
  "tools": ["aws_cli", "iam_analyzer", "access_analyzer"],
  "allowedTools": ["aws_cli", "iam_analyzer"]
}
```

## Usage Prompts:
1. Find unused IAM roles and users in my account
2. Analyze which permissions are actually being used by this role
3. Create a least-privilege policy for my Lambda function
4. Identify cross-account access risks in my policies
