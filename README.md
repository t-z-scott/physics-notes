# Physics 2002 Notes
A website to display my Physics 2 notes, for fellow struggling students.
## TODO
- [ ] Fix the [inline math issue](#inline-math).
- [ ] Clean up the formatting.
- [ ] Add more pages.
- [ ] Make a script to convert Obsidian-flavored markdown to GitHub-flavored markdown (currently doing it manually).
- [ ] Use CSS (or a framework) to make the pages look nicer.
- [ ] Add the other topics in my repo (includes Introduction to Cybersecurity, Computer Organization and Design, etc.).

---

## Bugs
_Note_: The files in the `notes` folder are in GitHub-flavored markdown, so they won't show up on my website (rendered in HTML). I have a couple ways to solve this:
- [x] Convert each page to HTML (doable with free tools online, but might not convert parts of the page).
- [ ] ~Find and import a script that displays Markdown files as HTML.~
- [ ] ~Make a script that displays Markdown files as HTML (not sure how to accomplish this).~

Thanks to [Mathjax](http://www.mathjax.org/) and the online Markdown to HTML converter at [W3Docs](https://www.w3docs.com/nx/marked), I was able to get the page in HTML and link it!
### Inline Math
MathJax renders the `$$` equations by default, not the inline math (ex: $`x+1`$). There's probably an edit I can make to fix this... I might have to make a config file.
