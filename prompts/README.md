# Prompt and Test Library (2024)

This library contains documented workplace prompt templates. Examples use placeholders or synthetic data; replace them only with information allowed by your organization and approved for the tool.

## Fields

- `id`: stable filename-friendly identifier.
- `title`: short name for the task.
- `task_category`: broad task type.
- `prompt_text`: reusable instruction, with bracketed placeholders to fill in.
- `expected_answer`: what a good response should contain.
- `known_failure_cases`: plausible ways the prompt or model may fail; these are risks, not claims of observed testing.
- `verification_steps`: checks a human must complete before use.
- `test_conditions`: tool, model/version, date, settings, and run count. `not_run` means no test has been performed. The date in current files records when this entry was authored, not a test date.
- `test_status`: `not_tested` until real tests are run and documented; then use `tested` only with recorded conditions and results.

## Add a prompt

Create one YAML file per prompt. Use a unique lowercase `id` matching the filename. Keep prompts clear about source limits, placeholders, uncertainty, and what must not be inferred. Include failure modes and human verification steps. Use only synthetic, clearly labeled examples in this repository.

## Test a prompt

Use an approved tool with synthetic or otherwise authorized input. Record the actual tool and model/version, date, settings, and number of runs. Save representative outputs or a concise results record, including failures and changes made. Update `test_status` to `tested` only after those real conditions and observed results are documented. Never infer a test result from a prompt’s wording or expected answer.

This library is a starting point, not evidence that a prompt is safe or reliable. Verify factual and policy claims against current authoritative sources and local rules.
