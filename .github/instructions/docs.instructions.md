---
applyTo: "**/*.md"
---

# Documentation Instructions

This document provides mandatory guidelines for creating and maintaining project documentation across the repository. It applies to all Markdown files and specializes rules for ADRs, PRDs, and Design docs.

## Scope and Purpose

- Ensure all docs are clear, consistent, and easy to maintain.
- Provide a standard workflow for planning, drafting, reviewing, and publishing documentation.
- Define default structures, formatting rules, and approval gates.

## General Guidelines

1. **Structure**: Organize documentation into clear sections with headings and subheadings.
2. **Clarity**: Use simple, concise language. Avoid unexplained jargon.
3. **Consistency**: Maintain a consistent style and format throughout the documentation.
4. **Examples**: Include examples and use cases to illustrate concepts.

## Inputs to Collect (before drafting)

- Purpose and scope of the document
- Target audience (developers, end-users, stakeholders)
- Key features, behaviors, or decisions to cover
- Existing related documentation or references

<PROCESS_REQUIREMENTS type="MANDATORY">
- If any inputs are missing or ambiguous, ask targeted questions and pause drafting until clarified.
- Confirm inferred inputs with the requester before proceeding.
</PROCESS_REQUIREMENTS>

## Document Review & Approval Process

1. **Initial Draft**: Create the first version following the general guidelines.
2. **Peer Review**: Request reviews from relevant stakeholders and address feedback.
3. **Approval**: Obtain final approval from the document owner before publishing.
4. **Publishing**: Place approved docs in the appropriate folder (e.g., `docs/`, `docs/ADRs/`, `plans/`).
5. **Archiving**: Establish a process for archiving outdated documents while ensuring they remain accessible for reference.

<CRITICAL_REQUIREMENT type="MANDATORY">
- Do not publish without owner approval.
- Save documents in their canonical locations with appropriate filenames.
- Update indices or README links when adding new documents.
</CRITICAL_REQUIREMENT>


## Documentation Structure Template

- Title
- Introduction
- Purpose and Scope
- Target Audience
- Key Features / Main Content
- Examples and Code Snippets
- Diagrams (if applicable)
- Maintenance and Update Instructions (if applicable)
- Conclusion
- References (if applicable)

## Formatting Guidelines

- Use Markdown with clear headings and subheadings.
- Prefer bullet points and numbered lists for clarity.
- Use fenced code blocks for code examples; include language identifiers.
- Link to related internal docs and authoritative external resources.
- Embed images/diagrams using Markdown. 
- Use Mermaid where supported for embedded diagrams like flowcharts and sequence diagrams.
- Ensure proper grammar and spelling.
- Avoid emojis and informal language.


### Design Documents
1. **Architecture**: Provide diagrams and component descriptions.
2. **Data Models**: Describe schemas and relationships.
3. **APIs**: Document endpoints, contracts, and authentication.
4. **User Interface**: Include wireframes, mockups, and accessibility notes.
5. **Security**: Outline security considerations and mitigations.
 6. **Location & Naming**: Save under `docs/design/` with a concise, descriptive filename.


## Saving and Location

- Default format: Markdown (`.md`).
- Default directory: `/docs/` with a relevant filename when no specialized folder applies.
- Use specialized directories and templates for ADRs (`docs/ADRs/`), PRDs (`docs/PRDs/`), and Design docs (`docs/design/`).

## Quality Gates

- All new or updated docs must pass a self-review for accuracy, completeness, and clarity.
- Ensure links are valid and images/diagrams render correctly in GitHub.
- Update indexes or README tables of contents where applicable.

