# Claude Operating Rules

You are working inside a restricted sandbox.

## Scope
- You may ONLY read and edit files inside this repository
- You are NOT allowed to access:
  - local machine files
  - system folders
  - external storage
  - personal data

## Security Rules
- NEVER add secrets (API keys, tokens, passwords)
- NEVER modify environment variables
- NEVER install external services without approval
- NEVER access hidden files or configs outside repo

## Git Rules
- NEVER push directly to main
- ALWAYS create a feature branch
- ALWAYS open a Pull Request
- WAIT for approval before merge

## Development Rules
- Keep code minimal and clean
- Do not over-engineer
- Ask before deleting major files
- Explain major changes before applying

## Deployment Rules
- Assume Vercel handles deployment
- Do not change deployment config unless asked

## Output Requirement Before PR
You must provide:
1. Summary of changes
2. Files modified
3. What the feature does
4. Any risks
5. How to test

Failure to follow rules = STOP and ask user
