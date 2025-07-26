---
description: Create a new claude command 
argument-hint: "prompt for command"
---

# Create Claude Command

Create a new custom slash command for Claude Code based on the specified requirements.

## Arguments
Command name and description: $ARGUMENTS

## Instructions

1. **Parse the request** - Extract the command name, scope (project/personal), namespace (if any), and functionality from $ARGUMENTS

2. **Determine command structure:**
   - **Scope**: Project commands (`.claude/commands/`) vs Personal commands (`~/.claude/commands/`)
   - **Namespace**: Check if command should be organized in subdirectories
   - **File naming**: Convert command name to valid filename (lowercase, hyphens for spaces)

3. **Create the command file:**
   - Use the appropriate directory structure
   - Generate the Markdown content with proper formatting
   - Include frontmatter if the command needs:
     - `allowed-tools` for bash commands
     - `description` for command documentation

4. **Command content structure:**
   ```markdown
   # Command Title
   Brief description of what this command does.
   
   ## Arguments (if applicable)
   Description of any arguments: $ARGUMENTS
   
   ## Instructions
   1. Step-by-step instructions
   2. Include specific actions to take
   3. Add any context gathering steps
   
   ## Output Format (if applicable)
   Specify expected output format or structure
   ```

5. **Advanced features to consider:**
   - **Arguments**: Include `$ARGUMENTS` placeholder if the command should accept parameters
   - **File references**: Use `@filename` syntax if the command should read specific files
   - **Pre-execution bash**: Use `!`command`` syntax if the command needs current system state
   - **Tool permissions**: Add frontmatter with `allowed-tools` if bash commands are needed

6. **Create the actual file:**
   - Use the `Edit` tool to create the new command file
   - Ensure proper directory structure exists
   - Test the command syntax is valid

7. **Provide usage instructions:**
   - Show the exact slash command syntax
   - Provide example usage
   - Explain any arguments or parameters

## Example Command Types

**Simple prompt command:**
```markdown
# Code Review
Perform a thorough code review focusing on best practices, performance, and security.

## Instructions
1. Analyze the current codebase
2. Identify potential issues
3. Suggest improvements
4. Provide specific examples
```

**Command with arguments:**
```markdown
# Fix Issue
Fix GitHub issue #$ARGUMENTS following our coding standards.

## Instructions
1. Use `gh issue view $ARGUMENTS` to get issue details
2. Understand the problem
3. Implement the fix
4. Write tests
5. Create descriptive commit
```

**Command with bash pre-execution:**
```markdown
---
allowed-tools: Bash(git status:*), Bash(git log:*)
---

# Git Summary
Provide a summary of the current git state.

## Context
- Current status: !`git status --porcelain`
- Recent commits: !`git log --oneline -5`
- Current branch: !`git branch --show-current`

## Instructions
Analyze the git state and provide insights about current work.
```

## Output
After creating the command, provide:
1. The full file path where the command was created
2. The slash command syntax to use it
3. Example usage scenarios
4. Any additional setup notes

