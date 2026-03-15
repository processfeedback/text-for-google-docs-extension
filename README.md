# Translations for Process Feedback for Google Docs

Community-maintained translation strings for the [Process Feedback for Google Docs](https://www.processfeedback.org/gdocs) Chrome extension.

The extension itself is proprietary. This repository contains only the localisation JSON files, which are licensed under the [MIT License](LICENSE) so anyone can contribute freely.

---

## Repository structure

```
translations/
  en.json       ← English (source of truth)
  es.json       ← Spanish
  fr.json       ← French
  ...
```

Each file is a flat key-value JSON object:

```json
{
  "feedback.submit": "Submit feedback",
  "feedback.placeholder": "Describe the issue...",
  "feedback.success": "Thanks! Your feedback was received."
}
```

Keys are defined in `en.json`. All other locale files must include the same set of keys.

---

## Adding or improving a translation

1. Fork this repository.
2. Copy `translations/en.json` and rename it to your locale code (e.g. `de.json` for German).
3. Translate each value. Do not change the keys.
4. Open a pull request with the title `[locale] Add/Update <Language>` (e.g. `[de] Add German`).

Please translate from the English source file, not from another translation. If a term has no natural equivalent, keep the English string and leave a comment in your PR explaining why.

### Locale codes

Use [BCP 47](https://www.ietf.org/rfc/bcp/bcp47.txt) language tags (e.g. `en`, `pt-BR`, `zh-Hans`).

### What makes a good translation

- Use natural, idiomatic language — not word-for-word literal translation.
- Match the tone of the English strings: concise, friendly, and direct.
- Preserve any placeholder tokens like `{{name}}` or `%s` exactly as they appear.
- If you are unsure about a term, add a note in your PR.

---

## Reviewing translations

Native speakers are encouraged to review open PRs for their language. Leave a comment on the PR if you spot an issue or have a better suggestion.

---

## Scope of this repository

This repository is for **translations only**. For bug reports, feature requests, or anything related to the extension itself, please [contact us](https://www.processfeedback.org/contact).

---

## License

MIT © Process Feedback contributors. See [LICENSE](LICENSE) for details.
