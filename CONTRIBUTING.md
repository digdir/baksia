# Contributing to Baksia

The Baksia site is generated from [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 
using the [Hugo](https://gohugo.io/overview/introduction/) static site generator.
We use YAML as front matter.

## Initial setup

1. Download and install [Git](https://git-scm.com/downloads) and clone the [baksia repository](https://github.com/digdir/baksia) to a local folder:
```bash
git clone https://github.com/digdir/baksia
```
2. We recommend downloading and using [visual studio code](https://code.visualstudio.com) with [this extension](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) for editing markdown.
3. [Download the latest Hugo](https://github.com/gohugoio/hugo/releases) (extended) for your platform, and place the executable in the baksia-folder.

## Build / Edit / Test

1. Open the baksia repo-folder in visual studio code
2. Run `hugo server --navigateToChanged`. Now baksia is running locally at http://loalhost:1313/
3. Edit and save a file in the `content`-folder to automatically get a new local build of the site refreshed in your browser.

## Deploy
Whenever changes are merged into the baksia main branch, an automatic deploy is updating https://baksia.digdir.no

If you don't have direct write access to the repo, you need to [create a fork](https://help.github.com/articles/fork-a-repo/)
and submit a [pull request](https://help.github.com/articles/about-pull-requests/).

## Links

 - [Markdown cheat-sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
 - [Hugo configuration](https://gohugo.io/overview/configuration/)
 - [Hugo front matter](https://gohugo.io/content/front-matter/)
