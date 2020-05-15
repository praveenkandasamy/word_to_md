Problem
=======

I usually make notes on word when studying. I need a fast way of
converting of from word to md. This will enable faster documentation on
GIT.

Solution
========

Use Pandoc via command prompt to efficiently convert word to doc. Use
slight modification to also grab the images to a subfolder.

Steps
=====

1.  Navigate to target folder on cmd

2.  Paste below code on cmd

*pandoc \--extract-media ./ input.docx -o output.md*

target file -- input.docx

destination file - *output.md*

subfolder containing images - / *media*

![](.//media/image1.png){width="6.268055555555556in"
height="0.4027777777777778in"}

3.  Go to git and drag and drop the md file and media folder and the
    content will be in production. Happy days. !!!!!!
