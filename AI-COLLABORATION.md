# AI Collaboration Philosophy

This document establishes the MÖBIUS Build Lab's philosophy and guidelines for working with AI coding agents and AI-assisted development tools.

## Core Philosophy

**AI is a development partner, not an unquestioned authority.**

In MÖBIUS Build Lab, we embrace AI as a powerful tool that can accelerate learning, improve code quality, and help us build better products. However, we recognize that AI systems have limitations, can produce incorrect or misleading outputs, and should never replace human judgment, understanding, and responsibility.

## Principles

### 1. Human Responsibility

- **Contributors remain responsible** for all work they submit, regardless of AI assistance
- **Understanding is mandatory:** You must understand what AI-generated code or documentation does
- **Validation is required:** You must test, review, and validate AI outputs before submitting
- **No blind trust:** Never submit AI-generated work without human review and understanding

### 2. Appropriate Footprint

AI-assisted work should leave a **lightweight, human-readable footprint** that enables:

- **Provenance:** Understanding where significant outputs came from
- **Accountability:** Identifying who was responsible for decisions and validation
- **Learning:** Enabling others to learn from the process
- **Review:** Allowing maintainers to assess the quality and safety of AI-assisted work

### 3. Proportional Documentation

Document AI activity in proportion to its significance:

- **Trivial interactions** (e.g., code formatting, simple refactoring) do not require documentation
- **Significant assistance** (e.g., architectural decisions, complex implementations, research) requires appropriate recording
- **Use judgment:** When in doubt, err on the side of transparency

## What to Document

For **significant AI-assisted work**, record the following in the appropriate location (collaborator profile, decision document, or PR description):

### Required Information

| Field | Description | Example |
|-------|-------------|---------|
| **Objective** | What you were trying to achieve | "Design a WhatsApp bot architecture for daily attention check-ins" |
| **AI Tool/Agent** | The AI system used | "Mistral Vibe CLI agent", "GitHub Copilot" |
| **Significant Work** | What the AI did | "Generated architecture diagram, proposed message flow, identified WhatsApp Business API limitations" |
| **Human Decisions** | Key choices you made | "Selected WhatsApp Business API over Twilio due to cost considerations", "Added manual override for edge cases" |
| **Files/Outputs** | What was affected | "docs/projects/attention-mirror/architecture.md", "projects/attention-mirror/bot.py" |
| **Result/Status** | The outcome | "Architecture accepted after review", "Prototype working, needs error handling" |

### Optional Information

- Time spent on AI-assisted portion
- Specific prompts used (if instructive)
- Alternatives considered and rejected
- Lessons learned or surprises encountered

## Where to Document

### Collaborator Profiles

Each contributor maintains a profile in `docs/collaborators/` that includes an **AI-assisted activity log** for significant interactions. Use this for:

- Ongoing AI-assisted work on assigned tasks
- Research and exploration activities
- Learning experiences with AI tools

### Decision Documents

When AI assists with architectural or product decisions, document the AI's role in the relevant decision document under `docs/projects/[project]/decisions.md`.

### Pull Request Descriptions

When submitting a PR that includes significant AI-assisted work, complete the AI involvement section of the PR template with:

- Brief description of AI assistance
- Your validation approach
- Any limitations or concerns

### Research Documents

When AI assists with research (e.g., technology evaluation, competitive analysis), document the AI's contributions in the research findings under `docs/projects/[project]/research/`.

## What NOT to Document

Do not create bureaucratic overhead:

- ❌ Every minor code completion or suggestion
- ❌ Simple formatting or style fixes
- ❌ Routine refactoring that doesn't affect logic
- ❌ Basic information lookups

The goal is **useful provenance**, not paperwork.

## Best Practices

### For Human Contributors

1. **Start with research:** Use AI to explore options, but form your own understanding
2. **Iterate with AI:** Use AI as a thought partner, not a replacement for thinking
3. **Validate rigorously:** Test AI-generated code thoroughly; AI often produces plausible but incorrect outputs
4. **Document decisions:** Record why you accepted, modified, or rejected AI suggestions
5. **Stay curious:** Ask "why" and "how" when AI provides solutions

### For AI Coding Agents

1. **Be transparent:** Clearly indicate when and how you used AI assistance
2. **Document your work:** Leave a trail of significant AI interactions
3. **Flag uncertainties:** Highlight areas where AI output may need extra human scrutiny
4. **Respect limits:** Do not make decisions reserved for human judgment (e.g., architectural choices, project direction)
5. **Follow the workflow:** Submit PRs, document activity, and participate in review

## Validation Guidelines

Before submitting AI-assisted work:

### Code

- [ ] I have read and understand all the code I'm submitting
- [ ] I have tested the code locally or verified its logic
- [ ] I have considered edge cases and error conditions
- [ ] I have checked for security vulnerabilities
- [ ] I have verified dependencies and compatibility

### Documentation

- [ ] I have verified the accuracy of AI-generated documentation
- [ ] I have checked links, references, and claims
- [ ] I have ensured the tone and style match project conventions
- [ ] I have validated technical explanations

### Design/Architecture

- [ ] I have evaluated trade-offs of AI-proposed solutions
- [ ] I have considered project-specific constraints
- [ ] I have verified that the design meets stated requirements
- [ ] I have identified any assumptions that need human validation

## Learning with AI

MÖBIUS Build Lab views AI as an opportunity to:

- **Accelerate learning:** AI can explain concepts, provide examples, and suggest approaches
- **Improve quality:** AI can catch bugs, suggest tests, and identify edge cases
- **Expand capabilities:** AI can help explore new technologies and paradigms
- **Increase efficiency:** AI can automate repetitive tasks and free time for creative work

However, **the learning happens in your engagement with the problem, not in the AI's output.** The most valuable use of AI is as a tool that helps you think more deeply, not as a replacement for thinking.

## Questions and Concerns

If you have questions about AI collaboration:

- Review this document
- Ask in the relevant Issue or PR
- Discuss with the Project Lead for guidance on specific situations

Remember: **You are the developer. AI is your tool.**
