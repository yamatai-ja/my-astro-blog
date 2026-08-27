# my-astro-blog

Draft-only Astro receiver for approved `article-package-v1.0` content.

## Safety

- This repository does not auto-publish.
- KRS/ChatGPT article packages must already pass the completed-article Gate.
- Astro content is stored with `draft: true`.
- No deployment workflow is enabled in this bootstrap.

## Intended content path

`src/content/blog/*.md`

The upstream adapter must preserve the completed article body and must not invent missing slug, description, facts, offers, or claims.
