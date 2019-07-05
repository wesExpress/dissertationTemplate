This template should conform to the guidelines for Georgia State's requirements. All of the back-end stuff is taken care of for you. All you need to do is compile the 'main.tex' file after adding/changing the various files in this package. It should go without saying that you should use this at your own discretion!

Before starting, go to 'frontcommands.tex' in the frontmatter directory and change your relevant info, like your name, your thesis title, etc. These will then be put where they need to go throughout the document.

When working, you should create tex files for each chapter and include them in the main 'chapter.tex' file. An example is there to show that you don't need any preambles or things for these files, they will simply be bare .tex files. The same goes for any appendices you might have.

I use `\bibitem' for my references, as seen in `backmatter/references/bib.tex.' If you don't like that, feel free to change it as you see fit. I have no idea if that will break anything, however!

If, for some reason, the format is incorrect, go to 'gsuFormat.tex' and adjust accordingly. This will be input by 'main.tex' and the whole document will change. As of Summer 2019, this document contains the approved formatting exactly.

I've added some basic commands in 'commands.tex' in the main directory, like \arcsec and \degr. Add your own commands at the bottom.

I've also added a more complicated command that adds a new chapter call: `\Chapter{}{}'. This allows you to have subtitles for chapters. I used this to place the reference for published chapters. Use it for whatever you want, and change it to fit your style. 

'packages.tex' should include everything you need, but add whatever you want. Be careful what you wish for, though, as sometimes LaTeX packages don't place nice with one another! DeluxeTable is known to work with this template just fine, so if you have the `.sty' file and prefer that to `tabular' go ahead and include it here.
