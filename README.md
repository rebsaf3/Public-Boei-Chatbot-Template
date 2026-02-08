```markdown
# Public Boei Chatbot Template Case Study
A practical case study and reusable template for building a basic business chatbot with strong guardrails, clean knowledge boundaries, and predictable output.

This repository is designed for end users, stakeholders, and first time builders who want a chatbot that behaves professionally and does not make things up.

This repo is public safe.
No tenant identifiers.
No internal urls.
No secrets.
No proprietary data.

## What this case study is about
Most chatbots fail in one of two ways.
They sound confident while being wrong.
They become a dumping ground for random features with no standards.

Public Boei is a template that focuses on the basics that actually matter.
Clear purpose
Clear sources
Clear behavior rules
Clear fallback when knowledge is missing
A structure you can reuse for future bots

This repo documents the approach and provides a clean starting point for future chatbot builds.

## What Boei does and does not do
What it does
1. Answers questions using approved knowledge provided to the bot
2. Keeps responses clear, consistent, and easy to read
3. Uses a mandatory no knowledge response when it cannot confirm an answer
4. Avoids hallucinations by enforcing source boundaries and refusal rules
5. Provides a repeatable structure for knowledge, prompts, testing, and updates

What it does not do
1. It does not invent facts, policies, or procedures
2. It does not pretend it performed actions it cannot perform
3. It does not browse the internet unless explicitly designed to do so
4. It does not store sensitive data in the repo
5. It does not silently change behavior without change control

## Who this template is for
1. Teams that need a basic chatbot but cannot accept unreliable answers
2. Builders who want a clean reference implementation with guardrails
3. Leaders who want a repeatable standard for simple bots across departments
4. Anyone who needs a public portfolio artifact that demonstrates safe agent work

## The core rule: no guessing
Boei follows one rule above all others.

If the answer is not confirmed by the approved knowledge, Boei does not guess.

Instead, Boei uses a no knowledge response that
1. Acknowledges the question
2. States it cannot confirm from approved content
3. Asks for the minimum missing detail or points to the next safe step

This is the difference between a helpful bot and a liability.

## How Boei is structured
This template is intentionally simple so it can be adopted quickly.

Typical components in this pattern
1. Purpose and scope definition
2. Approved knowledge set
3. Behavior rules and guardrails
4. Output formatting expectations
5. No knowledge fallback
6. Test pack for regression and quality
7. Change control for safe iteration

The platform can change.
The structure and rules should not.

## Guardrails demonstrated in this case study
1. Approved sources only
Boei uses only the knowledge you provide as the source of truth.

2. No invention
No new steps, facts, requirements, or links are added unless present in approved content.

3. Refusal and fallback
When content is missing or ambiguous, Boei responds with no knowledge rather than filling gaps.

4. Output discipline
Boei does not expose internal notes, routing signals, or tool traces.
It responds like a professional assistant.

5. Clarity over fluff
Short, direct answers.
Clear steps when steps exist in the knowledge.
No filler.

## How to explore this repo
Fast review path
1. Start with the README to understand scope and rules
2. Review the guardrails and no knowledge behavior rules
3. Review the knowledge folder structure and how content is organized
4. Review the test pack and failure rules
5. Review change control to see how updates are governed

This path is designed so non technical stakeholders can evaluate safety and usefulness quickly.

## Testing and quality control
A chatbot template is only credible if it is testable.

The test pack should cover
1. Common questions the bot is expected to answer
2. Edge cases that try to cause guessing
3. Ambiguous prompts that should force clarification
4. Out of scope prompts that should be refused
5. Formatting and tone expectations

Automatic fail conditions
1. Any invented fact presented as true
2. Any fabricated link, policy, or instruction
3. Any claim that the bot performed an action it cannot perform
4. Any output that ignores the no knowledge rule

## Operations and change control
This template treats prompts and knowledge like production assets.

Every update should follow a simple, boring process.
1. Proposed change documented in an issue
2. Change reviewed for safety and accuracy
3. Tests run against the new version
4. Change recorded in a change log
5. Release created for visibility

This prevents drift and makes behavior predictable.

## Engagement and inquiry prompts
If you want to use this template, these questions will speed up implementation.

1. What questions must the bot answer on day one
2. What knowledge is approved and who owns it
3. What topics are out of scope
4. What does no knowledge mean in your org, escalate or ask for details
5. What is your tolerance for ambiguity, strict or flexible
6. Who reviews changes and how often

## How this case study helps your organization
1. Faster delivery of basic chatbots with consistent standards
2. Lower risk of invented answers
3. Clear governance that leadership can understand
4. A repeatable pattern for expanding to more bots later

## Public safe note
Before publishing updates, verify no sensitive info is included.
If a detail is not required to explain the design, remove it.

## License
MIT
```
