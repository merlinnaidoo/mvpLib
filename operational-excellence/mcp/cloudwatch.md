Usage Prompts:
Connect to CloudWatch metrics and create custom dashboards
Query application logs across multiple log groups
Set up automated alerting for critical system metrics
Analyze performance trends over time

Configuration
{
  "name": "cloudwatch",
  "description": "CloudWatch metrics and logging MCP server",
  "prompt": "You provide access to CloudWatch metrics, logs, and alarms through standardized MCP protocols for monitoring and observability.",
  "tools": ["cloudwatch_api", "logs_api", "metrics_api"],
  "allowedTools": ["cloudwatch_api", "logs_api"]
}
