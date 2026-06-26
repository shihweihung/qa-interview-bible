# Style Guide

## Purpose

This guide defines the default writing style for QA Interview Bible. The goal is consistent, professional Markdown documentation suitable for a public engineering knowledge base.

## Tone and audience

- Write for engineers, QA professionals, and hiring managers.
- Use a professional, neutral, and practical tone.
- Prefer clarity over cleverness.
- Explain concepts so they remain useful outside a single company context.

## Core writing standards

- Use Markdown only.
- Keep one primary topic per page.
- Use sentence case for headings.
- Use one `#` heading per file.
- Prefer short paragraphs and clear lists.
- Define acronyms the first time they appear when they may be ambiguous.
- Prefer active voice unless passive voice is clearer.

## Heading structure

Recommended article structure:

```md
# Title

## Summary

## Main content

## Interview questions

## Generalized example

## References
```

If a page needs a different structure, keep the hierarchy logical and shallow.

## Markdown rules

- Use `-` for unordered lists.
- Use fenced code blocks with a language tag when possible.
- Use inline code for commands, paths, filenames, variables, and identifiers.
- Keep tables only when they clearly improve readability.
- Do not use raw HTML unless Markdown cannot express the content cleanly.

## Code and command examples

- Keep examples minimal and explain why they matter.
- Remove company names, hostnames, tokens, IDs, and private paths.
- Use placeholders such as `example-service`, `example.com`, or `sample_user`.
- Add context before large code blocks.

## Examples and case studies

- Generalize all examples.
- Focus on the engineering lesson, not the employer story.
- Replace specific metrics, names, and timelines when they reveal private context.
- If a real scenario is used, describe it as a generalized pattern.

## Link style

- Prefer official documentation for external technical references.
- Link internal pages when they add useful context.
- Avoid linking to low-signal or promotional sources unless necessary.

## Content quality bar

Every article should be:

- accurate
- reusable
- educational
- scannable
- public-safe

## Avoid

- confidential details
- emotional or adversarial language
- vague claims without explanation
- filler content
- unexplained jargon
- copy-pasted AI output without review
