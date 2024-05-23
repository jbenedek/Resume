# Resume
Typeset in LaTeX,

A style file (resume.sty) has been included to clean up .tex files. This file should be in the same directory as the .tex files.

pdf.sh is a bash script to generate a PDF file, 1 for each .tex files.

clean.sh removes all temp files, such as .aux, .dvi, .out, .tmp, and .log.

## Git Hub Actions

This repo uses GHA workflows to generate a PDF file for all .tex files. This results in an artifact being uploaded to the workflow.
The uploaded artifact is a zip file containing all pdf files generated.
