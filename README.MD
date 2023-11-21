# Pipe-Up project report using LaTex.

> Warning: **Do not remove any file from this folder if you want it to compile correctly**

In order to build and compile, first, set up your GNU/Linux system with the neccessary dependencies.

First, update your system:

``` sudo apt-get update```

``` sudo apt-get upgrade```



Then, install the neccessary dependencies and command line tools to be able to build the LaTex file and compile it into a .pdf:

``` sudo apt-get install texlive-xetex ```

``` sudo apt-get install texlive-latex-base```

``` sudo apt-get install texlive-fonts-recommended```

At this point, you should be able to compile the .tex file into a .pdf:

``` pdflatex report.tex ```

The report.pdf file will appear in the same directory as the .tex file.


Common errors that might be encountered:

Error 1: ```LaTeX Error with Sphinx: file `titlesec.sty' not found```

This issue can generally be solved by installing the following package:

``` sudo apt install texlive-formats-extra```

If it does not, then you will need to install the below package

``` sudo apt install texlive-full```


Error 2: ``` LaTeX Error: `xcolor.sty' not found when including tikz```

This error can be solved by installing the following package:
``` sudo apt install texlive-latex-recommended```