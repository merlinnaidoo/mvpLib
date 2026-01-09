# CloudFront MCP Server

## Description
MCP server for CloudFront CDN management, focusing on global content delivery optimization, cache performance, and edge location strategies.

## Installation

```bash
npm install @aws/cloudfront-mcp-server
```

## Configuration

```json
{
  "mcpServers": {
    "cloudfront": {
      "command": "npx",
      "args": ["@aws/cloudfront-mcp-server"],
      "env": {
        "AWS_REGION": "us-east-1",
        "AWS_PROFILE": "default"
      }
    }
  }
}
```

## Available Tools

### Distribution Management
- `create_distribution` - Create CloudFront distributions
- `get_distribution` - Retrieve distribution details
- `update_distribution` - Modify distribution settings
- `delete_distribution` - Remove distributions
- `list_distributions` - View all distributions

### Cache Optimization
- `create_cache_policy` - Custom cache behavior policies
- `get_cache_policy` - Retrieve cache policy details
- `update_cache_policy` - Modify caching rules
- `create_origin_request_policy` - Origin request configurations
- `get_real_time_log_config` - Real-time logging setup

### Performance Monitoring
- `get_distribution_metrics` - CloudWatch metrics access
- `list_invalidations` - Cache invalidation history
- `create_invalidation` - Invalidate cached content
- `get_streaming_distribution` - RTMP distribution details

### Security and Access
- `create_origin_access_identity` - S3 bucket access control
- `get_origin_access_identity` - OAI configuration details
- `create_field_level_encryption_config` - Data protection setup
- `list_public_keys` - Manage public keys for signing

### Edge Functions
- `create_function` - CloudFront Functions deployment
- `describe_function` - Function details and status
- `update_function_code` - Deploy function updates
- `test_function` - Function testing capabilities

## Key Use Cases

### Global Performance Optimization
```bash
kiro chat "Optimize my CloudFront distribution for global users with focus on cache hit ratios and edge performance."
```

### Cache Strategy Implementation
```bash
kiro chat "Design cache behaviors for my web application with different TTL settings for static and dynamic content."
```

### Edge Computing Setup
```bash
kiro chat "Implement CloudFront Functions for request/response manipulation to improve performance and user experience."
```

## Performance Metrics

The server provides access to CloudFront metrics:
- Cache hit/miss ratios by edge location
- Origin response times
- Viewer request patterns
- Bandwidth utilization
- Error rates (4xx/5xx)
- Popular objects analysis

## Optimization Features

### Intelligent Caching
- Automatic cache behavior recommendations
- TTL optimization based on content type
- Compression settings optimization
- HTTP/2 and HTTP/3 configuration

### Geographic Performance
- Edge location performance analysis
- Regional cache hit ratio optimization
- Price class recommendations
- Origin shield configuration

### Security Integration
- WAF integration for performance
- SSL/TLS optimization
- HSTS configuration
- Origin access control