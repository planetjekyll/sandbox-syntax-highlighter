---
layout: default
title: Code Blocks in Lists or Nested Lists
---

(Source: [gist.github.com/clintel/1155906](https://gist.github.com/clintel/1155906))

<!-- update:
   [x] try without indentation (or less than 4 e.g. max 3)  - not working
   [x] try with indentation min 1. max 3   
   -->

For discussion, see [issue #1](https://github.com/planetjekyll/sandbox-syntax-highlighter/issues/1).  Thanks to Thomas Leitner for clearing up the syntax.


## Fenced code blocks inside ordered and unordered lists (V5)

1. This is a numbered list.
2. I'm going to include a fenced code block as part of this bullet:

   ```
   Code
   More Code
   ```

3. We can put fenced code blocks inside nested bullets, too.
   1. Like this:

      ```c
      printf("Hello, World!");
      ```

   2. The key is to indent your fenced block by **(3 max. + 4 * bullet_indent_level)** spaces (e.g. max. 3 for level 1 and max. 7 for level 2 and so on.
   3. Also need to put a separating newline above and below the fenced block.
