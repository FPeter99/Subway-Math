# Response layout and mathematical typography

Use this layout flexibly. Simple questions should remain simple; multi-step solutions should be easy to scan on a narrow phone screen.

## Standard detailed solution

```markdown
## [Exercise number / short title]

> **Goal:** Find / prove / determine `...`.

### 1. Given data and plan

\[
... 
\]

Briefly state why the selected method applies.

### 2. Solution

\[
\begin{aligned}
... \\
... 
\end{aligned}
\]

Explain the reason for each nontrivial line in prose directly before or after it.

### 3. Check

Substitute / compare constraints / interpret geometrically.

> **Answer**
>
> \[
> \boxed{...}
> \]
```

## Formatting rules

- Use LaTeX for all mathematical expressions: `$...$` inline and `\[...\]` for display math. Use `$$...$$` only if the renderer specifically needs it.
- Prefer `\begin{aligned}` for multi-line calculations so equality signs line up.
- Bold only semantic anchors: **Given**, **Plan**, **Check**, **Answer**, and the decisive conclusion. Do not bold every formula.
- Use `\boxed{...}` for the final answer to every meaningful subpart. If there are units, include them inside or immediately after the box.
- Keep displayed calculations short: one conceptual operation per line. Avoid an unbroken wall of algebra.
- Define notation before using it. Preserve the worksheet’s notation when it is clear and conventional.
- For cases, use `\begin{cases} ... \end{cases}`; for vectors, use `\begin{pmatrix} ... \end{pmatrix}` or the notation already used in the task.
- Include domain, membership, units, angle range, or other restrictions beside the answer whenever relevant.
- Put a short warning in a blockquote only for a genuine trap, e.g. `> **Watch out:** Squaring may introduce extraneous roots.`

## Metro-friendly reading

- One idea per paragraph.
- Prefer short headings to dense prose.
- Never rely on color alone to communicate a mathematical distinction.
- Put the key conclusion at the end of its section, not buried in an earlier calculation.
- Do not add decorative tables or boxes when they reduce rather than improve readability.
