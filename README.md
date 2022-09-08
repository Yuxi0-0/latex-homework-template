latex-homework-template
=======================

This is a simple latex tempate for students' homework.


YOU DON'T need to download any compiler(latex toolkits), Just follow steps below:

1. registered yourself to an online latex editor:https://www.overleaf.com/.
2. Fork this repo to your own github account.(uppper right of this page Fork)
3. Back to overleaf, start a new project, choose to import this repo from github.
4. You can now be able to typesetting using latex.

Some useful sources:
math symbols https://www.cmor-faculty.rice.edu/~heinken/latex/symbols.pdf

basic usage check https://www.overleaf.com/learn/latex/Tutorials learn latex in 30mins

warmly suggestion:
to insert code samples, consider using minted package
## Features

Here are just a few features of this homework template.

1. Title page.
2. Problem markers.
3. Configurable problem numbers (see the last 3 problems for an example).
4. Some commonly used math macros.

## Screenshots

### The Cover Page:

![Cover page](/images/latex1.png)

### Big Oh Example Problem:
![Example problems 1](/images/latex2.png)

### Automata & Pseudocode Problems:
![Example problems 2](/images/latex3.png)

### Statistics Problem:
![Example problems 3](/images/latex4.png)

### Proof Problem:
![Example problems 4](/images/latex5.png)

### Adjustable Problem Numbers
![Example problem numbering](/images/latex6.png)

## Installing

1. First you'll need LaTeX. Instructions on obtaining it can be found here:
   http://latex-project.org/ftp.html
2. Compiling from the command line will look like the following:

   ```bash
   $ latexmk homework.tex
   ```
3. Or you can use [TeXShop][texshop] or a similar native client to typeset the
   LaTeX file.

## Credit

When first starting with LaTeX, I came across [this template][credit] and used
it as a base for starting my template. As you can see, it is pretty similar.

## License

This code is distributed under the MIT license. For more info, read the
[LICENSE](/LICENSE) file distributed with the source code.

[texshop]: http://pages.uoregon.edu/koch/texshop/
[credit]: http://www.latextemplates.com/template/programming-coding-assignment
[twitter]: https://twitter.com/jldavis
