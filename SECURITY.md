# Security Policy

## Scope

QA Interview Bible is a public documentation repository. The most important security rule is to keep confidential and sensitive information out of the repository.

## Do not include

- secrets, tokens, API keys, or passwords
- internal URLs, hostnames, or environment details
- customer or employee data
- private screenshots
- production logs with sensitive data
- proprietary diagrams, documents, or source excerpts

## Public content requirements

- Treat every committed file as public.
- Sanitize all examples before publishing.
- Generalize all incidents and case studies.
- Remove metadata that could identify a company, product, customer, or person.

## Reporting a repository security concern

If you discover that sensitive information was committed by mistake:

1. Do not amplify the exposure.
2. Remove the content from the repository history as quickly as possible.
3. Rotate any exposed credentials immediately.
4. Review adjacent files, screenshots, and examples for related exposure.

If the issue is about the repository configuration or documentation process, open a private issue only if the report itself can be shared safely. Otherwise handle it off-platform first.

## Vulnerability disclosure note

This repository is primarily a documentation project rather than a deployed application service. Security reports should focus on:

- accidental disclosure of sensitive information
- unsafe publishing practices
- harmful or misleading instructions
- insecure automation or repository configuration
