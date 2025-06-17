# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the "Awesome Claude Code" repository - a curated list of resources for enhancing Claude Code workflows. The repository primarily consists of a README.md containing categorized links to slash-commands, CLAUDE.md files, workflows, and documentation related to Claude Code.

## Repository Structure

- `README.md` - Main awesome list with categorized resources
- `CONTRIBUTING.md` - Guidelines for contributors
- `code-of-conduct.md` - Code of conduct for contributors
- `.claude/commands/add-new-resource.md` - Slash-command to help users add new resources

## Resource Categories

The awesome list is organized into five categories:
1. **Supplementary Resources & Blogs** - External tools and blog posts
2. **Slash-Commands** - Individual command files (ordered alphabetically by command name)
3. **CLAUDE.md Files** - Project configuration files (ordered alphabetically by repository name)
4. **Workflows** - Collections of related commands working together
5. **Official Documentation** - Anthropic-provided resources

## Entry Format Standards

Each entry follows this format:
```markdown
[`/command-name`](link) by [author](author-link)  
Brief description explaining the value and functionality of the resource.
```

For workflows, use descriptive names instead of command names:
```markdown
[Workflow Name](link) by [author](author-link)  
Description of what the workflow accomplishes and its components.
```

## Contribution Guidelines

- All entries must be in alphabetical order within their category
- Descriptions should be 1-2 sentences explaining the resource's value
- Use permalinks for GitHub resources when possible
- Only submit publicly accessible resources
- Focus on resources that provide genuine value to Claude Code users

## Adding New Resources

Use the `/add-new-resource` slash-command to guide the process of adding new entries. This command acts as an interactive wizard to help format submissions correctly and create proper pull requests.

## Quality Standards

Resources should meet one or more criteria:
- Provide genuine value to Claude Code users
- Demonstrate innovative usage patterns
- Follow best practices for Claude Code resources
- Come from reputable sources
- Work with current Claude Code versions

## Submission Process

New resources are added via pull request by editing README.md. The `/add-new-resource` command helps ensure proper formatting and categorization before submission.