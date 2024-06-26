# Physics 2002 Notes
A website to display my Physics 2 notes, for fellow struggling students.
## Markdown Pages Index
- [Chapter 18](https://github.com/t-z-scott/physics-notes/blob/main/docs/notes/ch18.md)
- [Chapter 19](https://github.com/t-z-scott/physics-notes/blob/main/docs/notes/ch19.md)
- [Chapter 20](https://github.com/t-z-scott/physics-notes/blob/main/docs/notes/ch20.md)
## Generated Website Code
The generated code for the GitHub page displayed at https://t-z-scott.github.io/physics-notes/ is in the `website-bug-testing` branch, located [here](https://github.com/t-z-scott/physics-notes/tree/website-bug-testing). What's in the main branch is the code and Markdown notes I wrote for this project.
## TODO
- [x] Fix the [inline math issue](#inline-math).
- [x] Add an Markdown index to this README.
- [ ] Add more pages.
- [ ] ~~_Optional_: Make a script to convert Obsidian-flavored markdown to GitHub-flavored markdown (currently doing it manually).~~
- [x] Use CSS (or a theme) to make the pages look nicer.
- [ ] _Optional_: Add the other topics in another repository (includes Introduction to Cybersecurity, Computer Organization and Design, etc.).

---

## Bugs
_Note_: The files in the `notes` folder are in GitHub-flavored markdown, so they won't show up on my website (rendered in HTML). I have a couple ways to solve this:
- [x] ~~Convert each page to HTML (doable with free tools online, but might not convert parts of the page).~~
- [ ] ~~Find and import a script that displays Markdown files as HTML.~~
- [ ] ~~Make a script that displays Markdown files as HTML (not sure how to accomplish this).~~

Thanks to [MathJax](http://www.mathjax.org/) and the online Markdown to HTML converter at [W3Docs](https://www.w3docs.com/nx/marked), I was able to get the page in HTML and link it. I've decided, however, that it would be easier to use [MDwiki](https://dynalon.github.io/mdwiki/#!index.md) to display the original Markdown pages and fix the [inline math issue](#inline-math) in one fell swoop.
### Inline Math
MathJax renders the `$$` equations by default, not the inline math (ex: $`x+1`$). There's probably an edit I can make to fix this... I might have to make a config file.
