Usage Prompts:
Analyze my AWS spending patterns across all services
Identify unused resources and potential cost savings
Compare Reserved Instance options for my workload
Generate a monthly cost optimization report

Configuration
{
  "name": "cost-analyzer",
  "description": "Comprehensive cost analysis and optimization recommendations for AWS resources",
  "prompt": "You are a Cost Analyzer specializing in AWS cost optimization. Analyze spending patterns, identify cost drivers, and provide actionable recommendations.",
  "tools": ["aws_cli", "cost_explorer", "billing"],
  "allowedTools": ["aws_cli", "cost_explorer"]
}
