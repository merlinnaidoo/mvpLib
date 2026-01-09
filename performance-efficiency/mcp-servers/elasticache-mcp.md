# ElastiCache MCP Server

## Description
MCP server providing comprehensive ElastiCache management capabilities for Redis and Memcached caching optimization and performance tuning.

## Installation

```bash
npm install @aws/elasticache-mcp-server
```

## Configuration

```json
{
  "mcpServers": {
    "elasticache": {
      "command": "npx",
      "args": ["@aws/elasticache-mcp-server"],
      "env": {
        "AWS_REGION": "us-east-1",
        "AWS_PROFILE": "default"
      }
    }
  }
}
```

## Available Tools

### Cache Cluster Management
- `create_cache_cluster` - Create Redis/Memcached clusters
- `describe_cache_clusters` - List and inspect cache clusters
- `modify_cache_cluster` - Update cluster configurations
- `delete_cache_cluster` - Remove cache clusters
- `reboot_cache_cluster` - Restart cluster nodes

### Performance Monitoring
- `get_cache_metrics` - Retrieve CloudWatch metrics
- `describe_cache_events` - View cluster events and logs
- `get_cache_parameter_group` - Review configuration parameters
- `describe_reserved_cache_nodes` - Check reserved instances

### Cache Optimization
- `create_cache_parameter_group` - Custom parameter configurations
- `modify_cache_parameter_group` - Update cache parameters
- `create_cache_subnet_group` - Network configuration
- `describe_cache_engine_versions` - Available engine versions

### Backup and Recovery
- `create_snapshot` - Manual cache snapshots
- `describe_snapshots` - List available snapshots
- `copy_snapshot` - Cross-region snapshot copying
- `delete_snapshot` - Remove old snapshots

## Key Use Cases

### Cache Performance Tuning
```bash
kiro chat "Analyze my ElastiCache Redis cluster performance and recommend optimization parameters for better hit ratios."
```

### Scaling Cache Infrastructure
```bash
kiro chat "Design a multi-AZ ElastiCache setup with automatic failover for high availability and performance."
```

### Cache Strategy Implementation
```bash
kiro chat "Implement a caching strategy for my application with appropriate TTL settings and eviction policies."
```

## Performance Metrics

The server provides access to key ElastiCache metrics:
- Cache hit/miss ratios
- CPU and memory utilization
- Network throughput
- Connection counts
- Eviction rates
- Replication lag

## Best Practices Integration

- Automated parameter tuning recommendations
- Performance baseline establishment
- Cache warming strategies
- Multi-AZ deployment guidance
- Security group optimization