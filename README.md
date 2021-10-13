# Obsibian Template for Gatsby Theme Primer Wiki

**👋Another Obsibian template that use [gatsby-theme-primer-wiki](https://github.com/theowenyoung/gatsby-theme-primer-wiki), Welcome to your new Foam Knowledge Base!**

## Examples

- [Demo](https://demo-wiki.owenyoung.com) - ([Source](https://github.com/theowenyoung/gatsby-theme-primer-wiki/tree/main/example))

- [Everything I Know by Owen](https://wiki.owenyoung.com/) - ([Source](https://github.com/theowenyoung/wiki))

- [Foam Demo](https://demo-foam.owenyoung.com/) - ([Source](https://github.com/theowenyoung/foam-template-gatsby-theme-primer-wiki))

- [Obsidian Demo](https://demo-obsidian.owenyoung.com/) - ([Source](https://github.com/theowenyoung/obsidian-template-gatsby-theme-primer-wiki))

- [Gatsby Starter Demo](https://demo-gatsby-starter-primer-wiki.owenyoung.com/) - ([Source](https://github.com/theowenyoung/gatsby-starter-primer-wiki))

## Features

- Support Local search, full-text search.

- Support Graph Visualisation with canvas.

- Support Tags, Tags First, Generating tag pages, also connecting with graph visualisation.

- Support [Gitbook](https://docs.gitbook.com/integrations/github/content-configuration#summary) styled `SUMMARY.md` for custom sidebar.

- Support `[[WikiLink]]`, But you'd better use [Link Reference Definitions](https://foambubble.github.io/foam/features/link-reference-definitions) with extensions, `"foam.edit.linkReferenceDefinitions": "withExtensions"`

- Support Light/Dark Theme

- Custom Header Nav Items

- Nested sidebar

- Support Google Analytics

- Support Sitemap/Robot

- SEO optimization

## Principles

Here are my main ideas/principles in designing this theme.

1. No vendor lock-in. The less vendor features you use, the better you'll be able to migrate, including this theme. So we should only write standard markdown. I like `[[WikiLink]]`, but I love standard markdown more. So we should always use standard markdown link `[text](https://example.com)`, or use [Wikilink](https://foambubble.github.io/foam/wikilinks) with [Link Reference Definitions](https://foambubble.github.io/foam/features/link-reference-definitions), and don't use any vendor locked-in feature. That give us the capability change our theme, or hosted place.

2. Use meta data instead of special characters. We should use `tags` as the document's metadata, not `#tag` in the plain text.

3. Use tags instead of categories. Minimal subfolders.

## Quick Start

### New Wiki

1. Press "Use this template" button at [obsidian-template-gatsby-theme-primer-wiki](https://github.com/theowenyoung/obsidian-template-gatsby-theme-primer-wiki/generate) (that's this repository!) to fork it to your own GitHub account. If you want to keep your thoughts to yourself, remember to set the repository private.

2. [Clone the repository to your local machine](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) and open it in Obsidian

3. Delete all `.md` files you don't need, Change Site settings at `.layouts/gatsby-config.js`, change your CNAME at `.layouts/static/CNAME`, change your icon at `.layouts/static/logo.png`, commit your changes, and push to github, change your page settings at Github, make sure you set the page branch to `gh-pages`, then when github actions runed, you can visit your site.

### Exist Wiki

1. Clone this repo to your local machine

```bash
git clone https://github.com/theowenyoung/obsidian-template-gatsby-theme-primer-wiki.git
```

2. Copy `.layouts`, `.github` `.gitignore` to your wiki folder.

### Local Preview

```bash

cd .layouts

npm i

npm start

```

### Deploy

Deploy to Github Pages, see `.github/workflows/deploy.yml`

## Obsidian Quick Start

If you're in a hurry, here's some quick places to dive in:

- The [[Command palette]] contains most of the commands you need to work with Obsidian. Just press `Ctrl/Cmd-P` and start typing.
- How to [[Create notes|create new notes]].
- How to create [[Internal link|internal links]]
- How to use Markdown to [[Format your notes]]
- How to [[embed files]], or embed other notes
- [[Keyboard shortcuts]]
- How to [[Working with multiple notes|open multiple files side by side]]
- Obsidian can be extended with [[List of plugins|plugins]]. Several are available by default, and can be enabled or disabled according to your needs.

If you want a more thorough introduction, including a bit about our philosophy, check out [[Obsidian]].

And if you'd like a gentle introduction, or just want to get started but don't know how, head over to [[Basic note taking]].

If you are a [Catalyst supporter](https://obsidian.md/pricing), and want to turn on Insider Builds, see [[Insider builds]].

## Workflows

Obsidian is a tool that can be used in many ways, from a simple list of notes to a very powerful knowledge management system. We suggest you start at your own pace, and build it into the tool you need.

Here are a few ways to get started:

If you want to just start taking notes, check out [[Basic note taking]]

If you already have a collection of notes in markdown format, just choose them for your Vault. Choose "Vault" in the lower left and select the directory your notes are in.

If you have notes from Roam Research, Notion, or other systems, [[Import data|here's how to import them]].

If you'd like to know more about Obsidian, you can [[Obsidian|read about our story]].

By the way, you can feel free to edit these help docs, but when you open it again, they will be overwritten. So, don't put anything in them you want to keep.

## I have questions.

Then you should join our [community!](https://obsidian.md/community). We have active Discord and Forums, and the community is generally quite helpful.
