% This Site is Static Now
% Midnight Salmon
% 2025-08-15

# This Site is Static Now

This blog started out on WordPress. I like WordPress! Or, I *liked* WordPress.
Ever since 5.0 introduced the Gutenberg block-based editor, WordPress has given
up on being a blogging platform in favour of competing with Wix and SquareSpace
as a general web publishing tool with WYSIWYG editing. That's nice for web
design shops selling trendy landing pages to businesses, but it sucks for
anyone who just wants a blog.

After tiring of wrestling with Gutenberg, I wrote
[scrumble](https://github.com/Midnight-Salmon/scrumble). Scrumble is a static
site generator. It takes a folder full of Markdown files representing blog
posts and top-level pages and generates a blog in simple semantic HTML and CSS.
I wrote my own SSG rather than use an existing one because they all seem to
have the same problem as post-Gutenberg WordPress: they want to support the
creation of any hypothetical website, with any layout. Off-the-shelf SSGs do
this via complex templating systems rather than a fiddly web interface. I don't
want either! Scrumble is simple: Markdown goes in, website comes out. It
generates exactly one kind of website: mine.

That's the main reason for scrumble's existence. Another is security. I'm not
one of those people who considers WordPress fundamentally insecure. After all,
it's good enough for the White House. However, in my day job, I see compromised
WordPress sites almost every day. This is almost always thanks to
vulnerabilities in plugins, an issue I avoided on my own WordPress site by just
not having any plugins. A static site is of course invulnerable to anything
short of an attacker gaining access to the hosting backend.

A blog is really the simplest kind of website. Unless you're a national news
outlet, you don't need a CMS. Plain text files and a script with a goofy name
are more than enough.
