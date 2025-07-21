# Claude Commands

AI-powered development commands that transform how you think, plan, communicate, and implement code. Each command embodies expert knowledge to elevate your development workflow from idea to deployment.

## 🚀 Commands

### `/commit` - Intelligent Git Commits
**Source control wizard with an obsession for perfectly crafted commits.**
- ✨ AI-powered commit message generation with conventional formats + emojis
- 🔍 Pre-commit validation (linting, tests, security)
- 🧠 Context-aware analysis using branch names and project history

### `/bluf` - Bottom Line Up Front  
**Communication strategist who despises buried leads.**
- 🎯 Transforms complex information into clear, actionable communication
- 📋 4 specialized formats (Decision, Status, Analysis, Problem)
- ⚡ Executive-ready output with key points first

### `/brainstorm` - Critical Requirements Analysis
**Critical-thinking requirements analyst who challenges assumptions.**
- 🤔 Aggressive assumption challenging with targeted questions
- 💡 2-3 solution alternatives with user value comparison  
- 📋 Generates structured analysis documents for PRD development

### `/create-prd` - Product Requirements Documents
**Seasoned product manager with obsession for clarity.**
- 📋 Vision-first 6-section PRD structure for junior developers
- ❓ Strategic questioning with multiple-choice options
- ✅ Transforms brainstorm analysis into implementable requirements

### `/generate-tasks` - Development Task Lists
**Experienced tech lead who breaks down complex features.**
- 🎯 Priority-based task breakdown with complexity indicators
- 🔗 Dependency mapping for optimal development sequencing
- 📁 Intelligent file path suggestions based on project patterns

### `/process-tasks` - Development Flow Management
**Senior engineering manager who optimizes development momentum.**
- 📦 Smart task batching for flow state vs. individual validation
- ⚡ Parallel work coordination with dependency awareness  
- 📊 Technical debt tracking with automated progress reporting

## 🔄 Complete Development Workflow

```
💡 Idea → 🧠 Brainstorm → 📋 Create PRD → 🔨 Generate Tasks → ⚡ Process Tasks → ✨ Commit → 📢 BLUF
```

### Real Workflow Example

```bash
# 1. Challenge the idea
/brainstorm "Users forget what they worked on yesterday"
# → Generates: docs/brainstorm/2024-01-15-standup-work-visibility.md

# 2. Create detailed requirements  
/create-prd "Yesterday's Work Filter - Use brainstorm analysis from 2024-01-15-standup-work-visibility.md"
# → Generates: docs/prds/2024-01-15-yesterdays-work-filter.md

# 3. Break down into tasks
/generate-tasks "Based on PRD: 2024-01-15-yesterdays-work-filter.md"
# → Generates: docs/tasks/2024-01-15-yesterdays-work-filter.md

# 4. Execute development
/process-tasks "docs/tasks/2024-01-15-yesterdays-work-filter.md"
# → Smart batching, parallel work, technical debt tracking

# 5. Commit changes
/commit
# → "✨ feat(dashboard): add yesterday's work filter for standup prep"

# 6. Update stakeholders
/bluf "Yesterday's Work Filter deployment: 85% reduction in standup prep time"
```

## ⚡ Key Benefits

**Complete Coverage**: From initial idea validation through deployment communication
**Expert Guidance**: Each command embodies years of professional experience
**Quality Standards**: Junior-developer-ready output with professional depth
**Workflow Integration**: Commands designed to chain together seamlessly
**Technical Debt Management**: Systematic tracking and resolution of development debt

## 🏗️ Command Structure

Each command follows a proven pattern:

```yaml
---
description: Clear value proposition
argument-hint: "<expected input format>"
---

# /command-name

[Expert persona with specific personality and expertise]

## Process
[5-step clear execution plan]

$ARGUMENTS
```

**Core Elements:**
- **Expert Persona**: Source control wizard, communication strategist, requirements analyst
- **Structured Process**: Clear steps from analysis to output  
- **Reference Materials**: Best practices, examples, and professional frameworks
- **Quality Standards**: Actionable output with concrete next steps

## 🚀 Getting Started

**Start anywhere in the workflow:**
- Got an idea? → `/brainstorm`
- Need clarity? → `/bluf` 
- Ready to code? → `/generate-tasks` or `/process-tasks`
- Time to commit? → `/commit`

**Command Chaining:**
```bash
# Feed outputs directly to next command
/brainstorm "idea" → /create-prd → /generate-tasks → /process-tasks
```

**Rich Context:**
All commands accept detailed context for better results. Include metrics, constraints, technical stack, and specific scenarios for optimal output.

---

*Transform your development practice with AI-powered expert guidance at every step.*
