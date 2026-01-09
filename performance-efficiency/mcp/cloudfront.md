Usage Prompts:
Configure CloudFront distributions for global content delivery
Optimize cache policies and TTL settings for better performance
Analyze cache hit ratios and origin request patterns
Set up custom origins and behaviors for different content types

Configuration
{
  "name": "cloudfront",
  "description": "AWS CloudFront CDN management MCP server",
  "prompt": "You provide CloudFront content delivery network management for optimizing global content distribution and performance.",
  "tools": ["cloudfront_api", "cache_api", "distribution_api"],
  "allowedTools": ["cloudfront_api", "cache_api"]
}
