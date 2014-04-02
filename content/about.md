---
title:      "About nanoc"
is_dynamic: true
---

nanoc is a flexible <span class="firstterm">static site generator</span> (<span class="firstterm">SSG</span>).

Static site generators transform content from one format, such as Markdown or AsciiDoc, into another format, usually HTML, and lay out pages so that the site’s look and feel is consistent across all pages. Static sites can be deployed to any web server.

nanoc is not:

a <abbr title="content management system">CMS</abbr>
: It does not help in managing content; it merely processes it. Management of content is usually done on the filesystem.

a web application
: nanoc is a command-line application. With nanoc, developing sites happens on a local machine, and the generated site is deployed when it is finished.

To do: mention target audience (basic Ruby knowledge)

Advantages of static site generators
------------------------------------

Static site generators have several advantages of classical content management systems:

fast
: Static files can be served fast. There is no database or templating layer that slows requests down. Additionally web servers will automatically set caching headers (such as `Last-Modified`) for static files, which reduce bandwidth usage.

secure
: Static sites do not contain dynamic content, and are therefore immune to most common attacks.

previewable
: Because static sites are developed locally, you can play around with the site to your heart’s content without affecting the live site.

versionable
: Static site generators commonly store their content in flat text files. This makes them an ideal candidate for source control. Because of this reason, many static sites are open-source.

NOTE: Just because static sites are safer than dynamic sites does not mean you don’t need to take security into account. Use strong passwords, don’t communicate credentials over plaintext, etc.

Why use nanoc?
--------------

nanoc is suitable for a wide variety of sites, including personal blogs, portfolios and product web sites. Some unique features that allow this include:

* support for various markup languages (Markdown, AsciiDoc, Textile, …)
* support for various templating languages (eRuby, Haml, Mustache, …)
* ability to write custom filters and helpers
* ability to pull in data from other sources (databases, web APIs, …)
* integration with various deployment mechanisms
* ability to run pre-deployment checks

To do: mention some well-known sites and how they use nanoc (nanoc.ws, GitHub dev, FOSDEM, Myst Online)

To do: mention programmability (querying items by attributes)

To do: mention metadata

To do: mention guard-nanoc

Similar Projects
----------------

There are several static website generators floating around. Some of them are like nanoc, and some of them aren’t similar at all. If nanoc doesn’t fulfill your needs, check out [this list of static site generators](http://staticsitegenerators.net/).
