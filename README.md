[![Build Status](https://travis-ci.org/nrri-web/nrri-web.github.io.svg)](https://travis-ci.org/nrri-web/nrri-web.github.io)

## Website for NRRI ##

This is a redesign of the [NRRI website](http://nrri.org). Currently, we're hosting the [redesign here](http://nrri-web.github.io), with GitHub Pages. Simple enough? This readme is aimed at new users, not developers.

## New user? Start here ##
First off, you'll need to create an account on [GitHub](https://github.com/join). Once you've done that, let someone in NRRI know, and they'll add you to the [NRRI organization page](https://github.com/nrri-web) and give you access to the website.

### New posts ###
To create a new post, head to [Prose.io](http://prose.io) and give Prose access to your GitHub account. Then, go to nrri-web (top right, underneath your GitHub username), then nrri-web.github.io>_drafts. You'll find templates for all the relevant post types: report, PDF report, teleseminar, presentation, whatever else gets added. The layouts drop-down can be used to specify the post layout, but I'll probably set the default as whatever the template is supposed to be.

Name your post whatever you'd like, and things on the backend will transform it into the right format. Type up your post and pick the appropriate metadata using the Meta Data button at the top-right.
> Make sure you pick at least one category, as the post will be displayed according to the category tags.

The Teaser section is where you put what gets displayed on the landing pages, so make it snappy. Also make sure you add the author; without an author, the field defaults to "National Regulatory Research Institute".

You can use the raw metadata section to specify more advanced things, but that should mostly be taken care of by the post templates.

Use the post preview at the top right to see the rendered version of your Markdown. The Prose editor has helpful formatting buttons along the top, so even if you don't feel like a Markdown expert, you can always use the buttons. Make sure that you save post changes manually, and click "Draft to Post" to publish. Add a little description of what you did (usually, publish post, or something like that) and click Commit.

Here, the magic takes over, and the site gets built and pushed to the gh-pages branch. Don't worry about all that. Give it about 3 minutes to build, and you'll see changes on the website.

## To-Do ##
- [x] Create post templates
- [ ] Build test/draft branch
- [ ] Write up explaining how the CI works
- [ ] General designing stuff, to come as we see it
