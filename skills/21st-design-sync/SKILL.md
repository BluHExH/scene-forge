---
name: 21st-design-sync
description: Read the current project's design tokens and publish them as a theme on 21st.dev. Use when syncing design system tokens, colors, fonts or spacing from the project into a shareable 21st theme.
---

# 21st Design Sync — publish your project's design as a theme

Take the design a project already ships (its light + dark CSS variables) and
publish it to the **public** 21st.dev theme library so anyone can preview,
bookmark, and apply it. Under the hood this is one CLI call:
`21st publish-theme <file.css> --name "…"`.
