# Repository Organization Structure

This document outlines the organizational structure for the Autonomous Infrastructure Platform repositories.

## 📊 Repository Categories

### Core Platform Services (5 repositories)
- `infrastructure-orchestrator` - Core deployment engine
- `mcp-server` - AI integration layer  
- `output-registry` - Resource sharing
- `stamp-registry` - Stamp catalog
- `multi-repo-coordinator` - Repository management

### LLM Agent Services (6 repositories)
- `llm-agent-engine` - Core AI framework
- `multi-repo-planner` - Cross-repository planning
- `cross-team-coordinator` - Team collaboration
- `governance-validator` - Policy enforcement
- `drift-detector` - Infrastructure monitoring
- `remediation-agent` - Automated remediation

### Platform Engineering Tools (4 repositories)
- `iac-cli` - Command-line interface
- `stamp-generator` - Interactive stamp creation
- `environment-composer` - Visual design
- `dependency-visualizer` - Relationship mapping

### Supporting Libraries (3 repositories)
- `platform-sdk-typescript` - TypeScript SDK
- `stamp-templates` - Template collection
- `platform-docs` - Documentation

## 🏷️ Repository Topics

### Standard Topics by Category
- **Core Platform**: `platform-core`, `infrastructure`, `orchestration`, `azure`
- **LLM Agents**: `ai-agents`, `llm`, `automation`, `intelligent-infrastructure`
- **Tools**: `developer-tools`, `cli`, `platform-engineering`, `devex`
- **Libraries**: `sdk`, `libraries`, `templates`, `documentation`

### Technology Topics
- `typescript`, `nodejs`, `azure`, `terraform`, `bicep`
- `mcp`, `llm`, `ai`, `docker`, `kubernetes`

## 👥 Team Structure

### Platform Core Team
- **Repositories**: Core Platform Services
- **Permissions**: Admin
- **Responsibilities**: Platform infrastructure, core APIs

### AI Agents Team  
- **Repositories**: LLM Agent Services
- **Permissions**: Admin
- **Responsibilities**: AI agents, intelligent automation

### Developer Tools Team
- **Repositories**: Platform Engineering Tools
- **Permissions**: Admin  
- **Responsibilities**: Developer experience, tooling

### Platform Users
- **Repositories**: All (read access)
- **Permissions**: Read
- **Responsibilities**: Platform consumers, feedback

## 🔒 Security Settings

### Branch Protection (All Repositories)
- Require pull request reviews: 2 reviewers
- Dismiss stale reviews: enabled
- Require status checks: enabled
- Require up-to-date branches: enabled
- Restrict pushes to main: enabled

### Security Features (All Repositories)
- Private vulnerability reporting: enabled
- Dependency graph: enabled
- Dependabot alerts: enabled
- Secret scanning: enabled
- Code scanning: enabled

## 📋 Standard Labels

### Priority Labels
- `priority/critical` (red)
- `priority/high` (orange)
- `priority/medium` (yellow)
- `priority/low` (green)

### Component Labels
- `component/api` (blue)
- `component/ui` (purple)
- `component/agent` (pink)
- `component/infrastructure` (green)

### Type Labels
- `type/bug` (red)
- `type/feature` (blue)
- `type/enhancement` (light blue)
- `type/documentation` (dark blue)

## 📈 Development Workflow

### Implementation Phases
1. **Phase 1**: Foundation (infrastructure-orchestrator, mcp-server)
2. **Phase 2**: Intelligence (llm-agent-engine, multi-repo-planner)
3. **Phase 3**: Tools (iac-cli, stamp-generator)
4. **Phase 4**: Advanced Features (governance, monitoring)

### Cross-Repository Coordination
- Organization-level project boards
- Shared GitHub Actions workflows
- Centralized dependency management
- Unified release process
