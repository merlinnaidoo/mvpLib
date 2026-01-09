Usage Prompts:
Monitor database performance and connection health
Optimize query performance and identify slow queries
Set up automated failover for high availability
Analyze database metrics and resource utilization

Configuration
```json
{
  "name": "rds",
  "description": "AWS RDS database management MCP server",
  "prompt": "You provide database management capabilities through AWS RDS for monitoring, optimization, and high availability configuration.",
  "tools": ["rds_api", "performance_insights", "cloudwatch_db"],
  "allowedTools": ["rds_api", "performance_insights"]
}
```
