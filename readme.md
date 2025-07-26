# Claude Commands

AI-powered development commands that transform how you think, plan, communicate, and implement code. Each command embodies expert knowledge to elevate your development workflow from idea to deployment.

## 📋 Table of Contents

- [Commands](#-commands)
- [Complete Development Workflow](#-complete-development-workflow)
- [Installation & Setup](#-installation--setup)
- [Key Benefits](#-key-benefits)
- [Command Structure](#️-command-structure)
- [Getting Started](#-getting-started)
- [Contributing](#-contributing)
- [License](#-license)

## 🚀 Commands

### `/commit` - Intelligent Git Commits
**Source control wizard with an obsession for perfectly crafted commits.**
- ✨ AI-powered commit message generation with conventional formats + emojis
- 🔍 Pre-commit validation (linting, tests, security)
- 🧠 Context-aware analysis using branch names and project history

### `/blog-post-review` - Blog Post Review & Editing
**Professional editor focused on clarity and engagement.**
- 📝 Comprehensive review of spelling, grammar, and readability
- 🔍 Content structure and flow analysis
- 💡 Style improvements and engagement suggestions
- ✏️ Technical accuracy and clarity checks

### `/sum` - Bottom Line Up Front (BLUF)
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

### `/create-command` - Custom Command Creator
**Meta-command architect for expanding your toolkit.**
- 🛠️ Creates new Claude commands with expert personas
- 📋 Structured command template generation
- 🎯 Clear argument handling and process definition
- 📁 Automatic file creation with proper formatting

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
/sum "Yesterday's Work Filter deployment: 85% reduction in standup prep time"
```

## 🔧 Installation & Setup

### Prerequisites
- [Claude](https://claude.ai) AI assistant access
- Git for version control
- A text editor or IDE

### Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jesse-spevack/claude-commands.git
   cd claude-commands
   ```

2. **Integration with Claude:**
   - Copy command files to your Claude workspace
   - Commands are markdown files that Claude can interpret
   - Use commands by typing `/command-name` followed by your input

### Directory Structure
```
claude-commands/
├── blog-post-review.md   # Blog post editing command
├── brainstorm.md         # Requirements analysis
├── commit.md             # Intelligent git commits
├── create-command.md     # Command creator
├── create-prd.md         # PRD generator
├── generate-tasks.md     # Task breakdown
├── process-tasks.md      # Task execution
├── sum.md                # BLUF communication
└── docs/                 # Generated documentation
    ├── brainstorm/       # Brainstorming sessions
    ├── prds/             # Product requirements
    └── tasks/            # Task lists
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
- Need clarity? → `/sum` 
- Ready to code? → `/generate-tasks` or `/process-tasks`
- Time to commit? → `/commit`
- Writing content? → `/blog-post-review`
- Need a new command? → `/create-command`

**Command Chaining:**
```bash
# Feed outputs directly to next command
/brainstorm "idea" → /create-prd → /generate-tasks → /process-tasks
```

**Rich Context:**
All commands accept detailed context for better results. Include metrics, constraints, technical stack, and specific scenarios for optimal output.

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Create New Commands**: Use `/create-command` to design new expert personas
2. **Improve Existing Commands**: Submit PRs with enhancements
3. **Share Workflows**: Document your successful command combinations
4. **Report Issues**: Help us improve by reporting bugs or suggesting features

### Contribution Guidelines
- Follow the existing command structure
- Include clear documentation and examples
- Test commands thoroughly before submitting
- Keep the expert persona consistent and engaging

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Transform your development practice with AI-powered expert guidance at every step.*
