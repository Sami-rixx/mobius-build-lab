# Attention Mirror - Requirements

**Project #001** | **Status:** Early Discovery / Pre-Development

> **Note:** This document captures our **current understanding** of requirements. It distinguishes between **known requirements**, **assumptions**, **open questions**, and **future possibilities**. Nothing in this document should be treated as a final V1 requirement until explicitly decided.

## Document Structure

This requirements document is organized into four categories:

1. **📋 Known Requirements** - Things we are reasonably confident about
2. **🤔 Assumptions** - Things we believe to be true but haven't validated
3. **❓ Open Questions** - Questions we need to answer
4. **🔮 Future Possibilities** - Ideas we're not ready to commit to

## 📋 Known Requirements

### Functional Requirements

| ID | Requirement | Priority | Status | Notes |
|----|-------------|----------|--------|-------|
| FR-001 | System must interact with users via WhatsApp | High | Draft | Platform requirement |
| FR-002 | System must allow users to track attention focus periods | High | Draft | Core functionality |
| FR-003 | System must provide feedback/reflection on attention patterns | High | Draft | Core value proposition |

### Non-Functional Requirements

| ID | Requirement | Priority | Status | Notes |
|----|-------------|----------|--------|-------|
| NFR-001 | System must respect user privacy | High | Draft | Data sensitivity |
| NFR-002 | System must be cost-effective to operate | Medium | Draft | Budget constraints |
| NFR-003 | System must be reliable for daily use | Medium | Draft | User trust |

### User Requirements

| ID | Requirement | Description | Priority | Status |
|----|-------------|-------------|----------|--------|
| UR-001 | Easy to get started | Minimal onboarding friction | High | Draft |
| UR-002 | Fits into daily routine | Natural integration with existing habits | High | Draft |
| UR-003 | Provides actionable insights | More than just data collection | Medium | Draft |

## 🤔 Assumptions

### Technical Assumptions

| ID | Assumption | Confidence | Validation Needed | Status |
|----|------------|------------|-------------------|--------|
| A-001 | WhatsApp Business API is accessible and affordable | Medium | Cost analysis, feature verification | Unvalidated |
| A-002 | We can build a conversational bot that users will engage with | Medium | User research | Unvalidated |
| A-003 | Users will have smartphones with WhatsApp | High | Market research | Unvalidated |
| A-004 | We can store user data securely | Medium | Technical research | Unvalidated |

### Business Assumptions

| ID | Assumption | Confidence | Validation Needed | Status |
|----|------------|------------|-------------------|--------|
| A-010 | There is demand for attention accountability tools | Medium | User interviews, market research | Unvalidated |
| A-011 | Users will pay for this service (future consideration) | Low | Market validation | Unvalidated |

## ❓ Open Questions

### Requirements Questions

| ID | Question | Category | Priority | Status |
|----|----------|----------|----------|--------|
| Q-001 | What is the minimal viable feature set? | Scope | High | Open |
| Q-002 | How often should users interact with the system? | Frequency | Medium | Open |
| Q-003 | What data do we need to collect to provide valuable insights? | Data | High | Open |
| Q-004 | How do we define and measure "attention"? | Definition | High | Open |
| Q-005 | What are the user's primary goals? (awareness, accountability, improvement?) | Goals | High | Open |

### Technical Questions

| ID | Question | Category | Priority | Status |
|----|----------|----------|----------|--------|
| Q-101 | What WhatsApp API should we use? (Business, Cloud, other?) | Platform | High | Open |
| Q-102 | What are the rate limits and costs of the chosen API? | Constraints | High | Open |
| Q-103 | Can we send messages proactively, or only respond? | Capabilities | High | Open |
| Q-104 | What backend infrastructure do we need? | Architecture | Medium | Open |
| Q-105 | How do we handle user authentication/authorization? | Security | Medium | Open |
| Q-106 | How do we store and process user data? | Data | Medium | Open |

### User Experience Questions

| ID | Question | Category | Priority | Status |
|----|----------|----------|----------|--------|
| Q-201 | How should the conversation flow work? | UX | High | Open |
| Q-202 | What tone should the bot use? (friendly, professional, playful?) | Tone | Medium | Open |
| Q-203 | How do we handle user errors or misunderstandings? | Error Handling | Medium | Open |
| Q-204 | How do we onboard new users? | Onboarding | Medium | Open |

### Operational Questions

| ID | Question | Category | Priority | Status |
|----|----------|----------|----------|--------|
| Q-301 | How do we monitor system health? | Operations | Medium | Open |
| Q-302 | How do we handle failures or outages? | Reliability | Medium | Open |
| Q-303 | What are the scaling considerations? | Scalability | Low | Open |

## 🔮 Future Possibilities

These are ideas that **might** become requirements, but we are **not** committing to them for V1.

### Potential Features

- Multi-user accountability groups
- Integration with calendar systems
- Gamification elements (streaks, badges, etc.)
- Advanced analytics and visualization
- Export capabilities (CSV, PDF, etc.)
- Voice message support
- Multi-language support
- Cross-platform support (beyond WhatsApp)

### Potential Technical Directions

- Machine learning for pattern detection
- Natural language understanding for flexible inputs
- Mobile app companion
- Web dashboard for deeper insights
- Open API for third-party integrations

## Requirements Evolution

This document will evolve through the following process:

1. **Discovery:** Add questions, assumptions, and initial requirements
2. **Research:** Validate assumptions, answer questions
3. **Decision:** Move validated items to known requirements or reject them
4. **Prioritization:** Order requirements for implementation
5. **Refinement:** Clarify and detail requirements before implementation

## Related Documents

- [Project Brief](./project-brief.md) - Overall project context
- [Architecture](./architecture.md) - Technical architecture exploration
- [Decisions](./decisions.md) - Record of decisions that affect requirements
- [Research](./research/) - Research findings that inform requirements

## How to Contribute

To help with requirements:

1. **Identify gaps:** Find missing requirements or unanswered questions
2. **Propose additions:** Create an Issue with your proposed requirement or question
3. **Conduct research:** Help validate assumptions or answer open questions
4. **Participate in discussions:** Share your perspective on requirements trade-offs
5. **Document findings:** Record research results that inform requirements

---

*Document created: 2026-08-24*
*Last updated: 2026-08-24*
*Status: Discovery Phase - All requirements subject to change*
