# Sustainability MCP Server

## Description
MCP server providing tools for AWS sustainability analysis, carbon footprint tracking, and green architecture recommendations.

## Installation
```bash
npm install -g aws-sustainability-mcp
```

## Configuration
```json
{
  "mcpServers": {
    "sustainability": {
      "command": "aws-sustainability-mcp",
      "args": ["--region", "us-east-1"],
      "env": {
        "AWS_PROFILE": "default"
      }
    }
  }
}
```

## Available Tools

### carbon_footprint_analyzer
Analyzes AWS resource carbon emissions and provides optimization recommendations.

**Parameters:**
- `resource_types` (array): AWS resource types to analyze
- `time_period` (string): Analysis period (1d, 7d, 30d, 90d)
- `regions` (array): AWS regions to include

**Usage:**
```
Analyze the carbon footprint of my EC2 instances and RDS databases over the last 30 days across us-east-1 and eu-west-1 regions.
```

### green_architecture_scanner
Scans infrastructure configurations for sustainability best practices and identifies improvement opportunities.

**Parameters:**
- `config_paths` (array): Paths to CloudFormation/Terraform files
- `scan_depth` (string): Analysis depth (basic, detailed, comprehensive)

**Usage:**
```
Scan my infrastructure templates for green architecture opportunities and provide sustainability recommendations.
```

### renewable_energy_optimizer
Recommends optimal AWS regions and scheduling based on renewable energy availability.

**Parameters:**
- `workload_type` (string): Type of workload (compute, storage, batch)
- `flexibility` (string): Scheduling flexibility (high, medium, low)
- `performance_requirements` (object): Latency and availability needs

**Usage:**
```
Optimize my batch processing workloads for maximum renewable energy usage while maintaining performance requirements.
```

### sustainability_reporter
Generates comprehensive sustainability reports with carbon metrics and improvement tracking.

**Parameters:**
- `report_type` (string): Report format (summary, detailed, executive)
- `baseline_date` (string): Comparison baseline date
- `include_forecasts` (boolean): Include carbon reduction projections

**Usage:**
```
Generate a detailed sustainability report comparing current carbon footprint against last quarter's baseline.
```

## Example Workflow

1. **Initial Assessment:**
   ```
   Use carbon_footprint_analyzer to assess current emissions across all regions and resource types over the last 90 days.
   ```

2. **Architecture Review:**
   ```
   Run green_architecture_scanner on infrastructure templates to identify sustainability improvements.
   ```

3. **Optimization Planning:**
   ```
   Apply renewable_energy_optimizer to recommend region and scheduling optimizations for batch workloads.
   ```

4. **Progress Tracking:**
   ```
   Generate monthly sustainability reports to track carbon reduction progress and ROI.
   ```