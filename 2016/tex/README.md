These are the .tex files for the 2016 application. The main file is Alter.tex, which acts as the root when you want to compile the application.

You can add or remove sections by adding an additional \include after the \mainmatter line, or by commenting the line out.

As long as the files are all in the same directory, you can include ./file.tex into the document just by saying \include{file}. No need to provide directory or declare the file type, just typing the name exactly as saved.

Otherwise, you don't need to touch anything when you update Alter.tex besides the year.

