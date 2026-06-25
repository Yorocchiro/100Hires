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

Continuation:

## AI-Powered SEO Content Production

### Topic
How practitioners use AI tools to scale SEO content production without sacrificing quality.

### What I Collected
- 10 expert sources documented in `/research/sources.md`
- LinkedIn posts from 8 experts in `/research/linkedin-posts/`
- YouTube transcripts from 2 channels in `/research/youtube-transcripts/`
- Blog summaries from Ahrefs and SurferSEO in `/research/other/`

### Why These Experts
I selected SEO experts who actively test and publish real results and not just 
theorists. Focused on people running AI SEO experiments on live sites 
(Matt Diggity, Nathan Gotch) and tool companies with proprietary data (Ahrefs, SurferSEO).

### Key Insight So Far
The experts agree: AI content at scale works only with editorial standards and 
topical relevance. Volume without quality gets penalized. Brand authority and 
entity consistency are becoming the core of modern SEO.