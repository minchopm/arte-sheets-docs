# Arte Sheets — operating procedures

Use these procedures as task-oriented reference. They describe public capabilities and verification steps, not private implementation. UI labels can vary by version.

## Procedure 1: Validate an imported workbook

### Before you begin

Keep the original file unchanged and use a working copy.

### Steps

1. Open the copy and identify three representative calculations: a total, a conditional calculation and a lookup if present.

2. Compare the displayed values and formula ranges with known reference answers.

3. Change one input and predict which cells should change; verify the result.

4. Inspect dates, decimal separators and text identifiers such as codes with leading zeros.

5. Export a copy, reopen it and repeat the checks on the important formulas.

### Expected result

Required formulas, values and formatting survive the intended round trip.

### If the result differs

Record the smallest failing workbook with synthetic data. Do not replace the original solely because the imported file opens.

## Procedure 2: Review a proposed collaborative edit

### Before you begin

Use a sample workbook and check the reviewer permissions.

### Steps

1. Identify the cell and explain the intended change in its comment context.

2. Use a suggestion rather than direct editing when review is required.

3. Compare the proposed formula with its input range and expected result.

4. Accept or reject the change after checking the effect on related cells.

5. Keep a dated export when the agreed calculation is finalized.

### Expected result

The accepted workbook contains reviewed changes with an understood effect.

### If the result differs

If a collaborator cannot edit, check document permissions and the selected account rather than sharing broader access unnecessarily.

## Report a repeatable problem

Record app/version, device/OS, selected mode, input conditions and the smallest failing step. Distinguish expected behavior from the observed result. Use synthetic examples and omit credentials or private records.

[Documentation index](README.md) · [Capabilities and limits](FEATURES_AND_LIMITS.md) · [Support and sources](PRIVACY_AND_SUPPORT.md)
