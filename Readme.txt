Option 1: Use CMD with the Node.js install method (recommended)
In Command Prompt, run:

text
npm install -g @juliusbrussee/caveman-code
This is the core install command that works on all platforms, including Windows CMD.

Option 2: Clone the repo and run the installer manually in CMD
If you prefer to use the official installer script but in CMD:

text
git clone https://github.com/JuliusBrussee/caveman.git
cd caveman
node bin/install.js --all
This does the same auto-detection and installation for all agents (Claude Code, Copilot, Cursor, etc.).

Set-up summary
These commands work in Command Prompt or Windows Terminal (CMD mode).

You need Node.js ≥18 installed first.

After install, type /caveman in each agent session to enable it.

######################## 

For agents that don’t auto-activate, you type /caveman once per session (not reinstall).
######################### 
Yes — Caveman mode works with Claude Code (Anthropic's AI coding tool) as well.

How it works for Claude Code
The Caveman plugin is originally built for Claude Code and cuts ~65–75% of output tokens while keeping technical accuracy.

For Claude Code specifically, the recommended install commands are:

bash
claude plugin marketplace add JuliusBrussee/caveman
claude plugin install caveman@caveman
Then restart Claude Code.

After installation, Caveman auto-activates every session for Claude Code.

You trigger it with:

text
/caveman
or say:

text
talk like caveman
and turn it off with:

text
normal mode
.

##################################### 
Multiple agents
The same installer script I gave you supports 30+ agents, including:

Claude Code

GitHub Copilot

Cursor

Windsurf

Cline

Codex

Gemini CLI

So: one-time install, then use /caveman in each agent’s session where you want it.