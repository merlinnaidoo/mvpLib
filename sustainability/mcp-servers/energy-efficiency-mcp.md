# Energy Efficiency MCP Server

## Description
MCP server focused on AWS energy efficiency optimization, power consumption analysis, and resource utilization improvements.

## Installation
```bash
npm install -g aws-energy-efficiency-mcp
```

## Configuration
```json
{
  "mcpServers": {
    "energy-efficiency": {
      "command": "aws-energy-efficiency-mcp",
      "args": ["--optimization-level", "aggressive"],
      "env": {
        "AWS_PROFILE": "default",
        "EFFICIENCY_THRESHOLD": "80"
      }
    }
  }
}
```

## Available Tools

### power_consumption_analyzer
Analyzes power consumption patterns across AWS resources and identifies energy waste.

**Parameters:**
- `resource_filters` (object): Filter criteria for resources
- `analysis_period` (string): Time period for analysis
- `granularity` (string): Data granularity (hourly, daily, weekly)

**Usage:**
```
Analyze hourly power consumption patterns for all EC2 instances over the last 7 days to identify energy waste opportunities.
```

### efficiency_optimizer
Provides specific recommendations for improving energy efficiency across AWS services.

**Parameters:**
- `optimization_targets` (array): Services to optimize (ec2, rds, lambda, ecs)
- `efficiency_goals` (object): Target efficiency improvements
- `constraints` (object): Performance and cost constraints

**Usage:**
```
Optimize EC2 and RDS instances for 25% energy efficiency improvement while maintaining current performance levels.
```

### graviton_migration_planner
Plans and estimates benefits of migrating workloads to AWS Graviton processors for better energy efficiency.

**Parameters:**
- `current_instances` (array): Current instance types and configurations
- `workload_characteristics` (object): CPU, memory, and I/O patterns
- `migration_timeline` (string): Preferred migration schedule

**Usage:**
```
Plan migration of current x86 instances to Graviton processors and estimate energy savings and performance impact.
```

### idle_resource_detector
Identifies and quantifies idle or underutilized resources consuming unnecessary energy.

**Parameters:**
- `utilization_threshold` (number): CPU/memory threshold for idle detection
- `observation_period` (string): Period to observe resource usage
- `resource_scope` (array): Resource types to analyze

**Usage:**
```
Detect idle EC2 instances and RDS databases with less than 10% utilization over the past 14 days.
```

### energy_scheduling_optimizer
Optimizes workload scheduling to minimize energy consumption during peak carbon intensity periods.

**Parameters:**
- `workload_profiles` (array): Workload types and flexibility
- `scheduling_constraints` (object): Business requirements and SLAs
- `energy_priorities` (object): Energy vs performance trade-offs

**Usage:**
```
Optimize batch job scheduling to run during low carbon intensity periods while meeting daily processing SLAs.
```

## Example Workflow

1. **Energy Baseline:**
   ```
   Use power_consumption_analyzer to establish current energy consumption baseline across all services.
   ```

2. **Waste Identification:**
   ```
   Run idle_resource_detector to find underutilized resources consuming unnecessary energy.
   ```

3. **Optimization Planning:**
   ```
   Apply efficiency_optimizer to get specific recommendations for energy improvements.
   ```

4. **Migration Assessment:**
   ```
   Use graviton_migration_planner to evaluate benefits of moving to more energy-efficient processors.
   ```

5. **Scheduling Optimization:**
   ```
   Implement energy_scheduling_optimizer recommendations for carbon-aware workload scheduling.
   ```

## Energy Efficiency Metrics

- **Power Usage Effectiveness (PUE)**: Infrastructure energy efficiency
- **Carbon Intensity**: gCO2/kWh by region and time
- **Resource Utilization**: CPU, memory, storage efficiency
- **Performance per Watt**: Computational efficiency metrics