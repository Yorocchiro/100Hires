# 100Hires Onboarding 

## Tools Installed

- Cursor IDE

- Claude Code (Anthropic) installed via Cursor Terminal using `npm install -g @anthropic-ai/claude-code`

- Codex (OpenAI) installed via Cursor Terminal using `npm install -g @openai/codex`

## Steps Completed

1. Installed Cursor IDE

2. Installed Claude Code and Codex via npm ( these are CLI tools, not Cursor

   extensions. The original instructions which told me to use the "Extensions" tab was briefly confusing and neither tool is distributed that way)

3. Logged into both tools via Cursor Terminal and Web Authentication

4. Created this GitHub repository

5. Committed and pushed this README

## Issues Encountered

- **PowerShell execution policy error**: Running `claude` and `codex` initially failed

  with a `PSSecurityException` because PowerShell blocks local scripts by default.

  I fixed by running `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`

  as Administrator.

- **Extensions tab confusion**: The original instructions said to find these tools

  under Cursors Extensions tab, but Claude Code and Codex are standalone CLI tools

  and not VS Code/Cursor extensions. What I just did was installing them

  directly via terminal and confirming they integrate fine through Cursors terminal.