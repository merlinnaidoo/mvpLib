Usage Prompts:
Trace application requests across distributed services
Identify performance bottlenecks in microservices architecture
Analyze service dependencies and call patterns
Generate service maps for complex applications

Configuration
```json
{
  "name": "xray",
  "description": "AWS X-Ray distributed tracing MCP server",
  "prompt": "You provide distributed tracing capabilities through AWS X-Ray to analyze application performance and service interactions.",
  "tools": ["xray_api", "trace_api", "service_map"],
  "allowedTools": ["xray_api", "trace_api"]
}
```
