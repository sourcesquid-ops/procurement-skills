# Contributing

Thanks for your interest in contributing to Procurement Skills.

This repository is an open-source library of **Claude-native procurement and supply chain skills**. Each contribution should be practical, reusable, and grounded in real workflows.

## What you can contribute

We welcome:

- New Claude skills for sourcing, procurement, logistics, trade compliance, supply chain planning, supplier management, and adjacent workflows
- Improvements to existing skills
- Better documentation, naming, packaging, and examples
- Bug fixes in exported project structure or instructions

## Contribution principles

Please make sure your contribution is:

- **Specific** – focused on one real business workflow
- **Reusable** – useful across companies, categories, or industries
- **Practical** – based on actual procurement / SCM work, not generic prompt ideas
- **Safe** – avoids legal, compliance, or operational overclaiming
- **Well named** – easy to understand from the file name alone

## File naming convention

Use this format for skill exports:

`skill-XX-short-name.zip`

Examples:

- `skill-02-rfq-drafting.zip`
- `skill-08-tariff-hs-lookup.zip`
- `skill-18-new-product-introduction.zip`

Guidelines:

- Use lowercase
- Use hyphens, not spaces
- Keep names short but descriptive
- Keep numbering sequential if you are adding an official new skill

## What each skill should include

Each submitted skill should ideally contain:

- A clear purpose
- Defined user inputs
- Expected outputs
- Practical instructions / system behavior
- Reasonable guardrails and limitations
- A name that matches the business task

## Quality bar

Before submitting, ask:

- Does this solve a real procurement or supply chain problem?
- Would a practitioner actually use this in day-to-day work?
- Is the output clear and actionable?
- Is the scope narrow enough to be dependable?
- Does the file name clearly describe the skill?

## How to contribute

1. Fork the repository
2. Add or update your skill export
3. Update documentation if needed
4. Submit a pull request with a clear explanation of:
   - what the skill does
   - who it is for
   - expected inputs and outputs
   - any limitations or assumptions

## Pull request naming

Use clear PR titles, for example:

- `feat: add supplier discovery skill`
- `fix: improve customs documentation checklist skill`
- `docs: clarify naming convention for exported Claude skills`

## Notes

- Do not upload confidential supplier, pricing, contract, or customer data
- Remove sensitive examples before contributing
- Prefer generalized templates over company-specific workflows

## Questions or ideas

If you are not ready to submit a pull request, open an Issue with:

- the workflow you want to solve
- the type of user
- sample inputs
- expected outputs

That makes it easier to shape the right skill before building it.

Thanks for helping build the open-source skills layer for procurement and supply chain.
