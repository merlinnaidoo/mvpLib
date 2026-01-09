Usage Prompts:
Set up Redis clusters for application caching
Configure ElastiCache for session storage and data caching
Monitor cache performance and hit ratios
Optimize cache eviction policies and memory usage

Configuration
{
  "name": "elasticache",
  "description": "AWS ElastiCache in-memory caching MCP server",
  "prompt": "You provide ElastiCache management capabilities for implementing high-performance in-memory caching solutions.",
  "tools": ["elasticache_api", "redis_api", "memcached_api"],
  "allowedTools": ["elasticache_api", "redis_api"]
}
