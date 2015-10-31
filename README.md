# jekyll-template
Website Template

## What is this?
[Jekyll][1] is a static site generator. This repo contains everything you need to quickly make a personal website. Follow the instructions here to set up a quick "flier" web page for yourself and push it to eecs.umich.edu/~your-uniqname. If you would like to go beyond a simple flier and build a portfolio webpage or even a blog, you will find guidance at the end.

## Preliminary
The first thing you need to do is copy the files in this repository to your own computer. One way to do this is to use the **Download ZIP** button on the right-hand side of [this page][2]. (Those of you who use git and GitHub know all about the other way...). Now extract the files and open the folder that contains them.

When editing your site's files, a good text editor can mean the difference between fun and drudgery. If you don't already have a favorite editor, try [Atom][3]. It's free, powerful, and flexible.

## 1. Configuring Jekyll
Now that you have the files on your computer, it's time to start making them your own. Begin by opening the file named `_config.yml` in the main directory. This file contains the information Jekyll uses to configure itself.

Replace all the placeholders in the "Setup" section of `_config.yml` with your own values:

```yaml
# Setup
title:            your-title
tagline:          your-tagline
baseurl:          / # change to /~uniqname/ for eecs.umich deploy
author:
  name:           your-name
  url:            your-other-website
  email:          your-uniqname@umich.edu
```

## 2. Making your flier
When people visit your website, the first page they see will be `index.html`. If you're like me, you would prefer not to edit raw HTML. Fortunately, Jekyll knows how to translate [Markdown][4] into HTML; all we need to do is write `index.md`. (Of course, we also wrote some HTML for you to make the navbar and basic layout. You can check it out in `default.html` and `head.html` if you're interested.)

[1]: https://jekyllrb.com/
[2]: https://github.com/umich-ee/jekyll-template
[3]: https://atom.io/
[4]: https://daringfireball.net/projects/markdown/
