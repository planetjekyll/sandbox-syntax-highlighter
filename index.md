---
title: Welcome
---


## Syntax Highlighter Examples

- Code Blocks (e.g. \`\`\`)
    - Code Blocks in Lists or Nested Lists
    - Code Blocks with Options (e.g. `lineno`)
    - Code Blocks with Escapes (e.g. `{{raw}}{{..}}{{endraw}}`)
- Inline Code (e.g. `\`code\``)
- Highlight Tag (e.g. `{{raw}}{{highlight}}{{endraw}}`)


### _config.yml  Settings

```yaml
highlighter: rouge

markdown: kramdown

kramdown:
  input: GFM
  hard_wrap: false
  syntax_highlighter: rouge
```

## References

**Jekyll F.A.Q.**

For more info see the [Jekyll F.A.Q.](https://github.com/planetjekyll/quickrefs/blob/master/FAQ.md) entries:

- Q: How can I get backtick fenced code blocks (e.g. \`\`\`) working (with kramdown)?
- Q: How can I turn on syntax highlighting in code blocks (with kramdown 'n' rouge)?
- Q: How can I turn off syntax highlighting in code blocks (with kramdown 'n' rouge)?

**Jekyll Docu**

- Syntax Highlighter

**Kramdown Docu**

- Using the Rouge Syntax Highlighter

**Rouge Docu**

- Language Examples 

**GitHub Pages Help**

- Syntax Highlighter

