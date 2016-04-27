# University of Applied Sciences Offenburg - Thesis LaTeX Template

# 1 TeX Live installation

[TeX Live](https://www.tug.org/texlive/) includes all the major TeX-related programs, macro packages, and fonts that are free software, including support for many languages around the world.

## 1.1 Linux based systems
Install the full version of TeX Live with all packages:  
***sudo apt-get install texlive-full***

## 1.2 Microsoft Windows
Download the [Windows installer](https://www.tug.org/texlive/).

# 2 LaTeX Editor

## 2.1 TeXstudio
TeXstudio is a program based on Texmaker, which integrates many tools needed to develop documents with LaTeX in just one application. Using its editor you can write your documents with the help of interactive spell checking, syntax highlighting, code completion and more. This editor provides a splitted editor/pdf screen view.  
[TeXstudio installation](https://apps.ubuntu.com/cat/applications/texstudio/)

## 2.2 Other
There exist further more LaTeX editors like Texmaker or TeXworks.

## 2.3 SCons build system
Alternatively you can build the thesis.pdf file using SCons.

Install SCons: ***sudo apt-get install scons***

Build: ***scons***

# 3 BibTeX

Execute BibTeX before compiling the template for the first time.
