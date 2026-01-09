Usage Prompts:
Analyze my AWS carbon footprint across all regions
Identify idle resources contributing to unnecessary emissions
Recommend Graviton instance migrations for my workloads
Schedule batch jobs during renewable energy peak hours

Configuration
{
  "name": "carbon-optimizer",
  "description": "Optimizes AWS workloads for minimal carbon footprint through intelligent resource management",
  "prompt": "You are a Carbon Optimizer focused on minimizing environmental impact of AWS workloads through data-driven optimization and green computing practices.",
  "tools": ["aws_cli", "cloudwatch", "ec2"],
  "allowedTools": ["aws_cli", "cloudwatch"]
}
