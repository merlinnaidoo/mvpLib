# Disaster Recovery Agent

Comprehensive disaster recovery planning, testing, and orchestration for multi-region AWS deployments.

## Configuration

```yaml
agent:
  name: disaster-recovery-agent
  type: reliability
  tools:
    - aws-cli
    - shell
    - read
    - write
  capabilities:
    - dr_strategy_planning
    - failover_orchestration
    - recovery_testing
    - rto_rpo_analysis
    - multi_region_coordination
```

## Usage Prompts

### DR Strategy Planning
```
Design disaster recovery strategy for my application:
- Current architecture: [describe your setup]
- Business requirements: RTO 4 hours, RPO 1 hour
- Budget constraints: [specify limits]
- Compliance requirements: [list any requirements]

Recommend DR patterns (pilot light, warm standby, multi-site) with cost analysis.
```

### Automated Failover Setup
```
Implement automated failover for my multi-tier application:
- Database: RDS with read replicas
- Application: ECS/EKS with ALB
- Storage: S3 with cross-region replication
- DNS: Route 53 health checks

Create failover automation with rollback procedures.
```

### DR Testing Framework
```
Create comprehensive DR testing framework:
- Scheduled failover tests
- Data integrity validation
- Application functionality tests
- Performance benchmarking
- Communication procedures

Generate test reports and improvement recommendations.
```

### Recovery Time Optimization
```
Analyze and optimize recovery times for:
- Database restoration from snapshots
- Application deployment automation
- DNS propagation delays
- Data synchronization lag
- User session recovery

Identify bottlenecks and implement improvements to meet RTO targets.
```

### Business Continuity Planning
```
Develop business continuity plan covering:
- Critical system dependencies
- Recovery priority matrix
- Communication protocols
- Vendor coordination
- Regulatory compliance
- Post-incident analysis

Include decision trees and escalation procedures.
```