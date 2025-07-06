+++
title="Advanced Obsidian"
date=2025-07-06
tags=['Obsidian']
draft=false
+++

My up-to-date [Obsidian](https://obsidian.md/) reference with solutions, opinions, preferences and conventions.

## Obsidian

- Keep up with the [official blog](https://obsidian.md/blog/) and [r/ObsidianMD](https://old.reddit.com/r/ObsidianMD/) (but not too much).

## Keybinds

- Use keybinds as much as possible.
- Document and maintain personal keybind conventions across different programs.

## Dataview

- Use dataview and templates as much as possible: Courses, Projects, Books, ...
- This lets you generate statistics, automatic lists, etc.

## Tags

- Create most tags as notes instead of always using native tags: ~~`#obsidian`~~.
- Use tags with atomic concepts: `#list`, `#comparison`.
- Use corresponding tags on templates to make them visible to dataview: `#book`.
- Mention tags on the top of the note: `Tags: [[Obsidian]], #list`

## Vault and note management

- Stick to using one vault if you can.
- Keep track of all Obsidian-related questions and issues.
- Keep track of personal conventions to keep the notes consistent.
- Keep the collection synced with mobile. Easiest with the [official service](https://obsidian.md/sync).
- Use a single folder for notes. Do not organize main notes by folders.
- Link pages together and use the (local) graph view.
- Imitate hierarcy when needed.
	- A) Set up automatic [Maps of Content (MOC)](https://obsidian.rocks/maps-of-content-effortless-organization-for-notes/)
	- B) Maintain manual lists of notes under top-level categories
- Add aliases by typing `---` & `aliases`. Aliases work automatically.
- Merge accidentally created duplicate notes with the `Note composer` core plugin.
- Use alternative link text where necessary: `[[link|link text]]`.
- Split a note if it grows too large.

## Tasks

- Use markdown syntax for tasks: `- [ ] do this thing`.
	- Dataview can pull these from any page.
- I haven't had a need for additional task plugins, at least for now.

## Frontpage

- Create a frontpage (along with a keybind) with the `Homepage` plugin.
- Pull the next incomplete tasks from different domains of life:

	  ```dataview
	  task from "Notes/Projects"
	  where !completed
	  limit 2
	  ```

## Linting

- Use `Linter` plugin for keeping notes clean and consistent.

## Daily notes

- Use `Daily notes` along with a personal template if you want to.

## Flashcards

- Generate and maintain flashcards with `Obsidian to Anki` plugin:
	- `word_in_finnish::word_in_english` (Basic and Reversed cards).
	- `This {cloze deletion syntax} is for generating cards with a part of the sentence hidden.`

## Location

- Track places with the `Map view` plugin.
- Generate the geolocation to the frontmatter along with a type field (library, restaurant, ...).

## Publishing

- [Reasons and how to Blog](/blog/reasons-and-how-to-blog) 🚧 

## WIP

- Calendar that "works".
- Dashboard (frontpage with metrics).
- RSS integration.
- Semantic links.
- ...
