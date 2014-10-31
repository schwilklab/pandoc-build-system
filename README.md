Templates for a pandoc document build system
============================================

Collected by Dylan Schwilk, http://www.schwilk.org

Styles and templates for a scholarly document build system with  [pandoc](http://github.com/jgm/pandoc). Designed to help my students set up a markdown workflow.

Most material copyright the original authors, see the git submodules "csl" and "templates".  Other bits borrowed from [Kieran Healy's](http://kieranhealy.org/) pandoc build system. See https://github.com/kjhealy/pandoc-templates and https://github.com/kjhealy/latex-custom-kjh


Examples
--------

There is an [example markdown file](examples/example.md) in the examples folder.  The [Makefile](examples/Makefile) allows building pdfs, html or docx output from this markdown source. Type "make" a the command line to make all three outputs.


Using for your own writing
--------------------------

- Clone this repository into something like ~/.pandoc or ~/write/pandoc-system
- Copy the example/Makefile to your project directory containing your markdown document and modify the PREFIX variable in the Makefile to point to this cloned folder
- Modify the BIB variable to point to your bibliography file
- run 'make pdf' or 'make docx' or 'make html'
