# Arte Sheets: documentation and examples

Browser-based spreadsheets, practical lessons and optional AI assistance.

Maintained by Arte Soft. [Official website](https://sheets.arte-soft.com/) · [Company](https://arte-soft.com/)

This public repository contains product documentation, reproducible workflow examples and a measurement protocol. It is not the application's source-code repository.

## Product overview

- Edit formulas, multiple worksheets, charts and pivot tables in a browser.
- Import Excel workbooks or CSV and export the results.
- Try browser-local workbooks without an account; cloud storage and sharing require an account and are subject to plan limits.
- Collaborate with comments, suggestions and document permissions.
- Learn with public guides and worked examples. Pro includes AI assistance and Academy features.

## Example: check a category total

Enter the following synthetic data in A1:B5:

| Category | Amount |
| --- | ---: |
| Tools | 18 |
| Seeds | 27 |
| Tools | 15 |
| Tools | -3 |

Use `=SUMIF(A2:A5,"Tools",B2:B5)`. The expected result is **30**. Change the final amount from -3 to -5; the expected result becomes **28**. These are arithmetic reference answers, not a claim that an application compatibility test has been run.

See the [learning library](https://sheets.arte-soft.com/en/learn/) and [open the editor](https://sheets.arte-soft.com/app/?lang=en).

## Evaluation

See [BENCHMARKS.md](BENCHMARKS.md) for the measurement protocol and [RESULT_TEMPLATE.md](RESULT_TEMPLATE.md) for a run report. **No measured benchmark results are published in this initial release.** Example inputs and expected answers are clearly distinguished from observed application results.

## Sources and freshness

Product overview prepared on 2026-11-04 from the [official product site](https://sheets.arte-soft.com/) and developer-provided product materials. Features, availability and pricing can change; consult the current app and official site. This is first-party documentation, not an independent review or evidence of superiority over another product.

## Feedback

Open an issue for documentation corrections or reproducible workflow problems. Include the product version, operating system and minimal reproduction. Do not post passwords, API keys, account identifiers, private media or customer data.
