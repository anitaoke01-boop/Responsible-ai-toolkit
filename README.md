# Responsible AI Toolkit

**Author:** Anita Adaugo Okezie

A small portfolio project for using AI responsibly at work. It gives professionals a plain-language guide for reviewing AI-assisted work and a reusable library of workplace prompt templates with expected-answer criteria, failure risks, and human verification steps.

## Contents

- [`guide/`](guide/README.md): practical field guide on appropriate use, sensitive information, source and figure checks, errors and bias, human review, and uncertainty.
- [`guide/checklist.md`](guide/checklist.md): one-page review checklist.
- [`guide/examples/`](guide/examples/): four clearly labeled illustrative error scenarios with flawed outputs, detection steps, and corrections.
- [`prompts/`](prompts/README.md): 15 YAML prompt templates and documentation for their fields and testing process.

All example data and scenario details are synthetic. Prompt records remain `not_tested`; this repository does not claim prompt test results. Verify factual, legal, regulatory, product, and organizational policy claims against current authoritative sources before relying on them. Follow workplace rules for approved tools and data.

## Use

Read the guide and checklist before reviewing AI-assisted work. Adapt prompts to the task using only approved data, then verify the output using the checks recorded in each YAML file. Record real test conditions and results before changing a prompt’s status to `tested`.
