Usage Prompts:
Recommend optimal instance types for my current workloads
Analyze CPU and memory utilization to suggest downsizing
Compare performance impact of different instance families
Create a rightsizing plan with cost-benefit analysis

Configuration
{
  "name": "rightsizing",
  "description": "AWS resource rightsizing recommendations based on utilization analysis",
  "prompt": "You are a Rightsizing specialist focused on optimizing AWS resource allocation by analyzing utilization patterns and recommending appropriate instance sizes.",
  "tools": ["aws_cli", "cloudwatch", "compute_optimizer"],
  "allowedTools": ["aws_cli", "cloudwatch"]
}
