## Bigger Series Wiki

This wiki serves as a knowledge base for mods in the Bigger Series.

## Contribution Notes

This repository is synchronized daily to the [Wiki.js instance](https://biggerseries.net).

You are able to contribute either on the Wiki directly, or via Git using this repository. However, there are some caveats, and things that'll need to be done while contributing. Don't worry if you forget any of these though, we can let you know (or we can fix them later).

### Use Markdown, Not HTML

Whenever possible, use Markdown instead of HTML files (Git) or the WYSIWYG editor (Wiki.js). This makes it easier to edit pages regardless of what way you choose to contribute. You *can* use HTML tags inside of the Markdown files if necessary, however; just don't go overboard.

As a note, there are currently pages on the Wiki that are written using the WYSIWYG editor (which were converted to HTML files). Those will need to be rewritten/migrated to Markdown at some point.

### Use HTML Image Tags, Not Markdown

This adds on to the bit above. Normal Markdown images dont really allow you to align text to the side of the image; if it does, then it shifts the text down to the corner, which doesn't look right. This is a spot where, if at all possible, you should use the HTML `<img>` tag, rather than the normal Markdown `![]()` images. Below is an example:

```html
<img style="float: left;" src="/biggerreactors/turbine/turbine_casing.png"></img>
**Turbine Casings** make up the frame and walls of the turbine.
```

### Include Metadata

Wiki.js adds metadata to each page automatically. If you believe it necessary, you can exclude it from your files and the bot will auto-generate it. However, its defaults arent always the best (for example, by default, it uses an all-lowercase page name). Below is an example of the metadata used in Markdown files; simply place this at the top of the file (the important ones are `title`, `published`, and `editor`):

```metadata
---
title: turbine
description: 
published: true
date: 2022-08-27T03:10:49.341Z
tags: 
editor: markdown
dateCreated: 2022-08-27T03:10:46.422Z
---
```

### Other Bits

Those are the main things, but in general there are a few other things that'll help:

- Try to match the style of any other pages that already exist. Feel free to reuse and modify existing files to save work!
- Check over the Wiki and see if there are any spots that need to link to the new page(s). You should have at least one, otherwise the page will be inaccessible by anything other than by URL directly.
- If the Wiki sidebar needs adjusting, add a comment in your pull request. The sidebar can't be modified in Git, so someone with Wiki admin privileges will need to manually add it when approving the request.