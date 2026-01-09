Usage Prompts:
Track carbon emissions data across AWS services and regions
Monitor energy efficiency metrics for compute resources
Generate sustainability reports and carbon footprint analysis
Set up alerts for high-emission resource usage patterns

Configuration
{
  "name": "sustainability",
  "description": "AWS sustainability and carbon tracking MCP server",
  "prompt": "You provide sustainability tracking capabilities for monitoring carbon footprint and environmental impact of AWS workloads.",
  "tools": ["sustainability_api", "carbon_api", "emissions_tracking"],
  "allowedTools": ["sustainability_api", "carbon_api"]
}
