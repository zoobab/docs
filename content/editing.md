---
title: "Editing"
---

The pages on this site are generated from the
[jeelabs/docs](https://github.com/jeelabs/docs) repository on GitHub.  The
format is [Markdown](https://learn.netlify.com/en/cont/markdown/) with some
additional "[shortcodes](https://learn.netlify.com/en/shortcodes/)", such as the
"Tip" at the end of this page.

#### If you have commit access

The "Edit this page" link (top right) opens GitHub's online text editor.  Changes
made this way will automatically update the site via a webhook - it's great
for fixing typos, small changes, etc.

#### If you don't have commit access

The "Edit this page" link leads to a page where you can "fork" the `docs`
repository and edit your copy. Please create a "pull request" to get your
changes incorporated into this site.

If you expect to make more changes, you can also add a [new
issue](https://github.com/jeelabs/docs/issues) on GitHub with your plans and
a request for direct edit/commit access as contributor.

#### More substantial changes

For larger changes, it's much more convenient to use Hugo's _live preview_
server mode, which shows the effect of each change as soon as it is saved to
file.  The basic steps to do this are:

1. install [Hugo](https://gohugo.io) (it runs on just about [any
   platform](https://github.com/gohugoio/hugo/releases))
1. clone the [jeelabs/docs](https://github.com/jeelabs/docs) repository
1. install the [Learn theme](https://github.com/matcornic/hugo-theme-learn)
   inside it
1. launch Hugo in server mode: `hugo server`
1. open <http://localhost:1313> in your browser
1. _extend and modify the documentation ..._
1. every time you save, the browser will update

{{% notice tip %}}
A convenient setup is to keep your editor and browser open,
side-by-side.
{{% /notice %}}
