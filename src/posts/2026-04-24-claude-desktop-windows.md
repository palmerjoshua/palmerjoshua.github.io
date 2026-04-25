---
title: "Claude Desktop on Windows: a follow-up to Hanff"
date: 2026-04-24
summary: "Reproducing the Native Messaging bridge finding on Windows. Three things Hanff's macOS post didn't cover."
readTime: "20 min read"
eleventyExcludeFromCollections: true
permalink: false
---

> This is placeholder content. The real post draft lives in
> `/mnt/user-data/outputs/blog-post-draft.md` and gets dropped in here once the layout is verified.

## Section heading

Paragraph text to verify body typography. Code inline like `Get-NamedPipeServerProcessId` should render in a monospace font.

```powershell
$roots = @(
  'HKCU:\Software\Google\Chrome\NativeMessagingHosts',
  'HKCU:\Software\Microsoft\Edge\NativeMessagingHosts'
)
foreach ($r in $roots) {
  Write-Host "checking: $r"
}
```

A blockquote:

> Use this for quoting Anthropic's documentation, Hanff's original post, or any other source.

A bulleted list:

- First item
- Second item with `inline code`
- Third item

That's enough placeholder content to verify rendering.
