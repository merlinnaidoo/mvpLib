# Backup Agent

Automated backup management and validation for AWS resources with cross-region replication and recovery testing.

## Configuration

```yaml
agent:
  name: backup-agent
  type: reliability
  tools:
    - aws-cli
    - shell
    - read
    - write
  capabilities:
    - backup_strategy_analysis
    - cross_region_replication
    - backup_validation
    - recovery_testing
    - retention_policy_management
```

## Usage Prompts

### Backup Strategy Assessment
```
Analyze my current backup strategy across all AWS services. Check:
- RDS automated backups and snapshots
- EBS snapshot schedules
- S3 cross-region replication
- Lambda function backup
- DynamoDB point-in-time recovery
- EFS backup policies

Identify gaps and recommend improvements with RPO/RTO targets.
```

### Cross-Region Backup Setup
```
Set up cross-region backup for my production environment:
- Primary region: us-east-1
- Backup region: us-west-2
- Services: RDS, EBS, S3, DynamoDB
- Retention: 30 days daily, 12 months monthly

Create backup policies and test restoration procedures.
```

### Backup Validation Testing
```
Create automated backup validation tests:
- Verify backup integrity
- Test restoration procedures
- Validate data consistency
- Check backup encryption
- Measure recovery times

Generate validation reports and alerts for failures.
```

### Disaster Recovery Runbook
```
Create disaster recovery runbook for complete region failure:
- Service priority matrix
- Recovery procedures by service
- Data restoration steps
- Network reconfiguration
- Application deployment
- Validation checkpoints

Include estimated recovery times and dependencies.
```