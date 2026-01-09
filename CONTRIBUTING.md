# Contributing to MVP Kiro Prompt Library

Thank you for contributing to the MVP Kiro Prompt Library! This guide explains how to submit your agent and MCP configurations.

## How to Contribute

### Method 1: GitHub Issues (Recommended)
1. Use our issue templates to submit contributions:
   - [Agent Contribution](../../issues/new?template=agent-contribution.md)
   - [MCP Server Contribution](../../issues/new?template=mcp-contribution.md)
2. Fill out all required fields
3. Wait for moderator review and approval
4. Moderator will add your contribution to the appropriate pillar

### Method 2: Pull Request
1. Fork this repository
2. Use the `TEMPLATE.md` file as your starting point
3. Create your configuration file following the established format
4. Submit a pull request with your changes
5. Wait for review and approval

## Contribution Format

All contributions must follow this exact format:

```markdown
## Usage Prompts

Your usage prompts here (one per line or numbered)

## Configuration
```json
{
  "name": "your-name-here",
  "description": "Your description here",
  "prompt": "Your prompt here",
  "tools": ["your", "tools", "here"],
  "allowedTools": ["allowed", "tools", "here"]
}
```

## Review Process

1. **Submission**: Submit via GitHub issue or pull request
2. **Review**: Moderators review for:
   - Format compliance
   - Content quality
   - Appropriate pillar placement
   - No duplicates
3. **Approval**: Approved contributions are added to the library
4. **Notification**: You'll be notified when your contribution is live

## Well-Architected Framework Pillars

Your contribution will be placed in one of these pillars:

- **operational-excellence**: Operations, monitoring, incident response
- **security**: Security assessments, compliance, threat detection
- **reliability**: Resilience, disaster recovery, availability
- **performance-efficiency**: Performance optimization, resource selection
- **cost-optimization**: Cost analysis, rightsizing, waste reduction
- **sustainability**: Environmental impact, resource efficiency

## Guidelines

- Use clear, descriptive names
- Write concise but comprehensive prompts
- Test your configurations before submitting
- Follow the established naming conventions
- Ensure your contribution adds unique value

## Questions?

Open a [general issue](../../issues/new) if you have questions about contributing.
