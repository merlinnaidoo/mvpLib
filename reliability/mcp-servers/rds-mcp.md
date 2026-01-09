# RDS MCP Server

Model Context Protocol server for comprehensive RDS backup, monitoring, and disaster recovery operations.

## Configuration

```json
{
  "mcpServers": {
    "rds-mcp": {
      "command": "npx",
      "args": ["@aws/rds-mcp-server"],
      "env": {
        "AWS_REGION": "us-east-1",
        "RDS_BACKUP_RETENTION": "30",
        "CROSS_REGION_BACKUP": "true"
      }
    }
  }
}
```

## Usage Prompts

### RDS Backup Analysis
```
Using RDS MCP tools, analyze backup configuration for all RDS instances:
- Automated backup settings
- Snapshot schedules and retention
- Cross-region backup status
- Point-in-time recovery windows
- Backup encryption status

Identify instances with inadequate backup policies and recommend fixes.
```

### Multi-AZ Failover Testing
```
Test Multi-AZ failover for RDS instances:
- Trigger controlled failover
- Monitor failover duration
- Verify application connectivity
- Check data consistency
- Document failover behavior

Create failover test reports with performance metrics.
```

### Read Replica Management
```
Optimize read replica configuration:
- Analyze read/write traffic patterns
- Recommend replica placement
- Configure cross-region replicas for DR
- Monitor replication lag
- Set up automated promotion procedures

Balance performance and disaster recovery requirements.
```

### RDS Performance Monitoring
```
Set up comprehensive RDS monitoring:
- Database performance metrics
- Connection pool utilization
- Query performance insights
- Storage and IOPS monitoring
- Automated alerting for anomalies

Create dashboards for proactive database management.
```

### Database Recovery Procedures
```
Create automated database recovery procedures:
- Point-in-time recovery scripts
- Cross-region restoration
- Data validation after recovery
- Application reconnection testing
- Performance verification

Document recovery procedures with step-by-step instructions.
```