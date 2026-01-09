Usage Prompts:
Query detailed cost and usage data across AWS services
Create custom cost reports and spending analysis
Set up cost anomaly detection and budget alerts
Analyze cost trends and forecast future spending

Configuration
{
  "name": "cost-explorer",
  "description": "AWS Cost Explorer data analysis MCP server",
  "prompt": "You provide AWS Cost Explorer capabilities for detailed cost analysis, reporting, and spending optimization insights.",
  "tools": ["cost_explorer_api", "billing_api", "budgets_api"],
  "allowedTools": ["cost_explorer_api", "billing_api"]
}
