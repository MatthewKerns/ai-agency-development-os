# Setup and Installation Guide

## Prerequisites

- A computer with internet access
- ~30 minutes for initial setup

---

## Step-by-Step Installation

### 1. Install Required Tools

1. **Install VS Code**
   - Download from [code.visualstudio.com](https://code.visualstudio.com/)
   - Follow the installation wizard for your operating system

2. **Install Claude Code CLI**
   - Open your terminal
   - Follow the official Claude Code installation guide
   - Verify installation by running `claude --version`

   > **Tip**: If you need help with installation, ChatGPT can guide you through the specific steps for your operating system.

### 2. Set Up Your Project

1. **Clone or download** this repository to your computer
2. **Open VS Code** and navigate to File > Open Folder
3. **Select the project folder** to open it as a workspace

### 3. Launch Claude Code CLI

1. Open the bottom pane in VS Code:
   - Look for three buttons in the top-right corner of VS Code (left pane, bottom pane, right pane)
   - Click the "Toggle Panel" button or use the keyboard shortcut (Cmd+J / Ctrl+J)
2. In the terminal panel, run:
   ```bash
   claude
   ```
3. Select your preferred model by running:
   ```
   /model
   ```
   - Select **Opus** for best results on complex system generation

### 4. Review the CLAUDE.md File

The `CLAUDE.md` file contains all the core instructions and context for this AI Agency OS:

- The 13 Principles (Foundation)
- Your role as the Architect
- Agency structure and team roles
- The agency flow
- Priority hierarchy
- Slash commands

Claude Code will automatically use this context in every session.

### 5. Start Using the System

Once your setup is complete:

1. **Review the folder structure** in `claude-code-os-implementation/`
2. **Start with the Executive Office** at `01-executive-office/START_HERE.md`
3. **Use slash commands** for daily operations:
   - `/daily-assessment [context]` - End of day productivity score
   - `/weekly-review [context]` - Weekly summary and planning
   - `/project-status` - Quick view of all projects

---

## Quick Start Commands

```bash
# Start Claude Code
claude

# Select model (recommended: Opus)
/model

# Check current working directory
pwd

# List files in current directory
ls -la
```

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Claude command not found | Reinstall Claude Code CLI and ensure it's in your PATH |
| VS Code terminal not opening | Try View > Terminal from the menu bar |
| Model not available | Check your Claude subscription and API access |

---

## Next Steps

After setup is complete:

1. Review `CLAUDE.md` for full system context
2. Start with the Executive Office (`01-executive-office/START_HERE.md`)
3. Set up your strategic alignment and OBG tracking
4. Begin tracking active client projects in Operations
5. Use daily/weekly workflows to maintain momentum

---

*For the original Claude Code OS framework, see [github.com/MatthewKerns/claude-code-os](https://github.com/MatthewKerns/claude-code-os)*
