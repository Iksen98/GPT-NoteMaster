# GTS NoteMaster (ServiceNow Ticket Documentation Agent)

**GTS NoteMaster** is a documentation assistant specialized in **ServiceNow ticket handling** for:

- **Rapid Response Team (RRT – AMER)**
- **GTS Onsite Support**

Its purpose is to **generate, review, and validate ticket documentation** in strict compliance with the applicable SOP based on the selected support profile.

## Key Principles
- No guessing. No vague notes. No generalizations.
- Enforces standards even if the user tries to skip them.
- Requires **profile activation** before generating ticket documentation.

## Profiles
### RRT (AMER)
- Mandatory first contact order and evidence requirements
- SLA awareness rules
- State transitions for Incidents and Tasks
- Transfer validation requirements

### Onsite Support
- Mandatory first contact (Teams preferred)
- Three Strike Rule enforcement
- Transfer procedure + Tag98 handling
- KPI awareness rules

## Repository Files
- **`agent_prompt.txt`** → Full system prompt for the agent (copy/paste into ChatGPT Agent setup).
- **`agents.md`** → Agent specification / operating contract (rules, behavior, guardrails, SOP links, and workflow).
- **`README.md`** → This overview + usage guidance.

## How to Use (Quick Start)
1. Create a ChatGPT Agent (web).
2. Paste the contents of **`agent_prompt.txt`** into the agent’s instructions/system prompt.
3. Start a conversation and **activate a profile** with one of the supported triggers.

### Profile Activation Examples
**RRT**
- `RRT`
- `Profile: RRT`
- `RRT Engineer`

**Onsite**
- `Onsite`
- `Profile: Onsite`
- `Onsite Engineer`

If no profile is selected, the agent will stop and request profile selection.

## Documentation Standard (Shared)
All Work Notes and Closed Notes MUST follow:
- **Where**: system/location/application/component affected
- **What**: action performed or issue identified
- **Why**: reason for action or explanation of outcome

Do NOT include:
- Who (captured by ServiceNow)
- When (captured by ServiceNow)

## Compliance & Rejections
The agent rejects or flags:
- Vague notes (e.g., “resolved”, “issue fixed”)
- Reference number used as resolution
- Technical content inside Additional Comments
- Missing evidence of contact attempts
- Incorrect status transitions
- Closure without full compliance

## License
Internal/Team use (define your preferred license if needed).
