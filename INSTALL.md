# System Analysis Documenter Skill - Installation Guide

## Prerequisites

- Claude Code installed and configured
- Claude Code skills directory accessible (usually ~/.claude/skills/)

## Installation Methods

### Method 1: Direct Installation from GitHub

1. Download the `.skill` file from the GitHub releases page
2. Install using Claude Code:
   ```bash
   claude skill install system-analysis-documenter.skill
   ```

### Method 2: Manual Installation

1. Clone or download this repository
2. Navigate to your Claude skills directory:
   ```bash
   cd ~/.claude/skills/
   ```
3. Copy the entire `system-analysis-documenter` folder to this directory

### Method 3: From Source

1. If you've downloaded the zip file from GitHub:
   ```bash
   unzip system-analysis-documenter-github-ready.zip -d ~/.claude/skills/
   ```

## Verification

To verify the skill is properly installed:

1. Start a Claude Code session
2. Ask Claude to help with system analysis documentation:
   - "Create a system analysis document for..."
   - "Help me write a系分 document for..."

The skill should automatically trigger and guide you through the process.

## Uninstallation

To remove the skill:

1. Delete the `system-analysis-documenter` folder from your Claude skills directory:
   ```bash
   rm -rf ~/.claude/skills/system-analysis-documenter
   ```

## Troubleshooting

- If the skill doesn't trigger automatically, try explicitly mentioning "system analysis document" or "系分"
- Make sure you're using Claude Code (not Claude Web or mobile app)
- Restart Claude Code if changes don't take effect immediately
- Check that the skills directory has proper read/write permissions

## Usage Tips

- Provide as much detail as possible about your system requirements
- The skill will guide you through the process step by step
- PlantUML diagrams will render beautifully in Yuque after export
- The quality assessment feature will help ensure your document meets standards