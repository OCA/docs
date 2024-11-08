---
title: Contribution guide
---
Docs are written in [Markdown format](https://www.markdownguide.org/) and rendered with
[Hugo](https://gohugo.io/).

Docs for a module named `example_module` should exist in the folder
`content/modules/example_module/index.md`.

You can use [Decap CMS](https://decapcms.org/) to contribute changes to docs. Just click
here: [✏️ CMS](https://oca-docs.netlify.app/admin/).

All contributions are covered by the [CC-BY-4.0 license](./LICENSE.txt).

## How this site is built

This part of the docs gets a bit technical. 🧑‍💻

This is a static site. Just old plain HTML files being served. That means that there's no database or controller involved. Well, actually our "database" is Git and our API provider is Github.

Of course, we don't write those HTML files by hand (almost). We use an SSG (Static Site Generator) called [Hugo](https://gohugo.io/). It helps reducing boilerplate. It also allows most of our content to be written in [Markdown](https://www.markdownguide.org/), with some extra (meta)data in their [front matter](https://gohugo.io/content-management/front-matter/) sections.

To make contributing easier for humans, we support contributions made by [Decap CMS in Open Authoring mode](https://decapcms.org/docs/open-authoring/). Basically, it's a more user-friendly UI for the same [fork, clone, push, PR](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests) process of any other Github repo. Of course, you can still do that directly instead, if you prefer.

Those HTML files are deployed in [Netlify](https://www.netlify.com/). They provide some extra benefits over plain Github Pages:

* [Github requires a server to bridge their OAuth with apps](https://decapcms.org/docs/github-backend/). Netlify does that for us.
* It integrates very well with Decap CMS (they're the authors, after all).
* A bot will build ephemeral sites for each PR and put a comment, so the new content can be reviewed functionally.
