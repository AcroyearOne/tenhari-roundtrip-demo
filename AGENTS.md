# How this site is built

Harbor & Pine is one plain HTML page (`index.html`) with one stylesheet (`styles.css`) and pictures in `assets/`. There is no build step and no script.

Rules for anyone, person or coding agent, who changes it:

1. Colours come only from the variables at the top of `styles.css` (`--ink`, `--accent`, `--green` and the rest). Never write a colour as a hex value inside a rule.
2. Every new rule in `styles.css` gets a one-line comment above it that starts with `/* Why: ` and says what the rule is for.
3. In the page's text an ampersand is written `&amp;`.
4. When you report what you changed, say which of these rules applied to the change.
