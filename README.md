Files README.md
---

Show README.md & HEADER.md gitlab style on your NextCloud !

![screenshot](screenshot.png)

With this app you can add a header and a footer to your nextcloud directories.
This can be use to explain the goal of a directory, describe the content of a folder ...

It show README.md in the way gitlab does.


# Usage 

  * Create a README.md file (case sensitive name) and fill it with the apropriate Markdown content.
  * You can do the same with the HEADER.md file.
  * It's rendered using the same markdown engine as the app. Before file list for the HEADER.md, after file list for the README.md
  * You can now use .README.md & .HEADER.md .It means that you can now hide those files.
  * You can also use .markdown extention.
  * It render now in public shared !

Now you can use template to customize the README.md/HEADER.md rendering.

  * Create your own theme and use your own content.css (see css/content.css file)
  * Rendering is done inside a div contenair with headermd or readmemd class.

# Markdow enabled plugins

The following markdown plugins are available, more to come, fill a issue if you need more.

 * Image sizing :  [markdown-it-imsize](https://www.npmjs.com/package/markdown-it-imsize)
 * Task list : [markdown-it-task-lists](https://www.npmjs.com/package/markdown-it-task-lists)
 * Code highlight : [markdown-it-highlightjs](https://www.npmjs.com/package/markdown-it-highlightjs)
 * Mermaid : [markdown-it-mermaid-plus](https://www.npmjs.com/package/markdown-it-mermaid-plus)
 * Katex : [markdown-it-katex](https://www.npmjs.com/package/markdown-it-katex)
 * image resize : [imsize](https://www.npmjs.com/package/markdown-it-imsize)
 * Anchord : [markdown-it-anchor](https://www.npmjs.com/package/markdown-it-anchor)
 * Table of Contents : [markdown-it-toc-done-right](https://www.npmjs.com/package/markdown-it-toc-done-right)


 # Admin section

 There is a new admin section in settings letting you tweak README.md

 * You have now some appearance options
 * Multi rendering engine are available
 * You can choose which filenames are to be used for header/footer content.


# Aknowledgments

This is a fork of [gitlab.univ-nantes.fr/uncloud/files_readmemd](https://gitlab.univ-nantes.fr/uncloud/files_readmemd/) as contributing in that private instance is currently not possible for me.
