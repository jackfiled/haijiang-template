# Prof.Jiang's Template

Professor Hai Jiang is a professor in the School of Computer Science, Beijing University of Posts and Telecommunications. In the homework for classes Prof. Jiang is teaching, he always asks students to write a survey with the topic related to his class.

In the requirements of his survey homework, he will provide a Word template and ask students to strictly follow this template. This template is reasonably comparable to the standard IEEE typesetting format, he said. And we are always much more comfortable formatting papers using LaTeX. However, if we just use the IEEETrans LaTeX template, you will find these two templates are so different that we call them comparable.

So I design this template. This template tries to provide the same format as the Word template on a pixel level. You can reference the template.tex file, which provides a redo instruction implementation of the official instruction file. You can compare the output PDF file with it, and you will find they only have differences on several lines. 

## Instructions

This repo comes with one style file (Haijiang.sty) and two LaTex files (main.tex and template.tex). The `Haijiang.sty` and the `main.tex` are the minimum files you need to write a paper. The `template.tex` can be used to generate the `template.pdf` for your reference.

First, four macros are defined to print the header part of the survey. The title, authors, and affiliations should be defined using the `TitleAndAuthor` macro. The abstract and keywords should be defined using the `Abstract` and `Keywords` macros, respectively. After starting the document, a `InsertHeader` macro should be invoked to render the pre-defined part.

Second, write the main text of the paper using the normal LaTeX tools. The paragraph skip, title skip, and lineskip are all well-tuned.

Last, invoke the `PrintBibliography` macro with your `bib` filename as the only argument.



 
