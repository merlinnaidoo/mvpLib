## Configuration

```
{
  "name": "monitoring-agent",
  "description": "AWS CloudWatch monitoring and alerting agent",
  "prompt": "You are an AWS monitoring expert. Help users set up CloudWatch alarms, analyze metrics, and troubleshoot monitoring issues.",
  "tools": ["aws_cli", "cloudwatch"],
  "allowedTools": ["aws_cli"]
}
```

## Usage Prompts:
1. Show me all CloudWatch alarms in critical state
2. Create a CPU utilization alarm for my EC2 instances
3. Analyze the last 24 hours of application logs
4. Set up custom metrics for my Lambda functions
