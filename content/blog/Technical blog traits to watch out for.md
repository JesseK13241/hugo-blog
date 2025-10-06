+++
title="Technical blog traits to watch out for"
date=2025-10-06
lastmod=2025-10-06
tags=['Blogging', 'Web development']
draft=false
+++


Lately I've been devouring various types of blogs, some for their high information density and some for the sheer fun of it.

Blogs come in different shapes and sizes. I've been collecting minor and major annoyances I've noticed as well as things that have positively surprised me. Some of these are things I haven't yet implemented for my own site. If there turns out to be a [good justification](https://en.wiktionary.org/wiki/Chesterton%27s_fence) for one of my complaints, I'll update the list accordingly.

Personality and individual style is important and should be celebrated. But if I ever end up taking over the world, use this page as a resource to prevent getting sent to the mines.

## Changelog

| Date       | Details |
| ---------- | ------- |
| 2025-10-05 | Created |

## General

- Readable fonts.
- No cookie banners, popups, ads or "share" links.
- Keep it minimal in terms of style & size (and the content in some cases).
- No excessive whitespace.
- Dark/light mode with [prefers-color-scheme](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme). **Support both and force neither**.
- Include a RSS feed (if you want your readers coming back).
- Do not update the modification date for the RSS on **non-significant** edits/fixes. Getting redundant RSS notifications isn't fun.
- No mandatory link previews on hover, leave that for browsers to implement.
- Copyright disclaimer on the footer feels weird.
- Be mobile friendly. Watch out especially for the random horizontal scroll bar.
- No `target="_blank"` links or other "features" that take the choice away from the user.
- Nice-to-have: Blogroll link.
- Nice-to-have: Clean site URLs (avoid dates and index.html).
- Nice-to-have: Link to the blog source code or to a replication resource.
- Nice-to-have: [/now](https://jessekokkaa.dev/now/) and some other [slashpages](https://slashpages.net/).
- Nice-to-have: **Tags** for quickly seeing what the blog as a whole is mostly about. These also play well with second brains and blog aggregators.

## Blog post listing

Blog sites should include a simple list of all the past blog posts.

- Include the creation date next to the blog title link.
- Titles should reflect the content. Don't make me guess.
- Grouping by year doesn't seem useful.
- Do not paginate by month.
- **Do not paginate at all**. Worst I've so far seen was 3 blog links per page...
- If you want to include short blog descriptions (or the full contents), make it **toggleable**.

## Blog post pages

- [Reading mode](https://support.mozilla.org/en-US/kb/firefox-reader-view-clutter-free-web-pages) should work, in case the author has made questionable choices with the font, layout or the column width.
- Semantic HTML in general.
- **Zooming in shouldn't cover the content** with unrelated elements (usually the header & footer). This way too common issue affects people with smaller screens/laptops.
- No unnecessary images, especially slop.
- If images or other slow-loading elements are included, eliminate the layout shift.
- No mailing list ads or other distractions in **middle** of the content.
- Fully justified typographic alignment is easy to get wrong. There shouldn't be high inconsistent jumps &nbsp; &nbsp; &nbsp; between &nbsp; &nbsp; words.
- Comment sections don't mix well with the blogging scene.
- Do not manipulate scrolling with custom JS.
- No "back to the top" arrows.
- No sticky elements that follow and take over space when scrolling.

