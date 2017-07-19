# Completely Unofficial Cardiff University Maths Thesis Template

## Structure
This template is divided as follows
```
./images
--- culogo.eps

./includes
--- acknowledgements.tex
--- bibliography.tex
--- declarations.tex
--- dedication.tex
--- preamble.tex
--- title.tex

abstract.tex
appendix1.tex
chapter1.tex
thesis.tex
```

Hopefully the files are named in such a way as to be fairly obvious what each does, but I'll
describe each below just in case.

The `preamble` file does all the package loading and sets up all of the styles used throughout
the document. It's fairly well commented.

The `title` file defines the titlepage. You will need to modify it to add your thesis title,
name and the year of submission.

The `declarations` file contains the declarations the university requires to accompany your thesis.
The last one requires you to insert a time period, the text that needs to be replaced is in
italics.

The `dedication` file should be modified to include a nice dedication or quote, or the reference to
it in the `thesis` file should be deleted.

The `acknowledgements` file should be modified to include people you would like to acknowledge or
thank, or the reference to it should be deleted from the `thesis` file.

The `abstract` file should contain a overall summary of your thesis.

The `appendix1` and `chapter1` files contain some lipsum text so you can render the template and
get a good idea of what it will look like.

`thesis.tex` is the file that pulls everything together. Most files are `\subfile`ed into the
file. This functionality (provided by the `subfiles` package) means that, if you follow the
example set by the chapter1 file, you can compile each chapter you write individually. When
your thesis gets long and intensive to compile, you may find this useful.

