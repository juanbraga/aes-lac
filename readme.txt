+---------------------------+
|          README           |
|           FILE            | 
|        aeslac.cls         |
|       (version 1.0)       |
|        2011.03.08         |
|                           |
|    Grupo de Audio - IIE   |
|   Facultad de Ingeniaria  |
|Universidad de la República|
|    elopez@fing.edu.uy     |
+---------------------------+

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%                                                         %%
%% NOTE: This text file uses UNIX line feed conventions.   %%
%% When (human) reading this file on other platforms,      %%
%% you may have to use a text editor that can handle lines %%
%% terminated by the UNIX line feed character (0x0A).      %%
%%                                                         %%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

1. Files in this distribution
=============================

The LaTeX class `aeslac', version 1.0, distributed in
March 08, 2011, was created based on the LaTeX class `aesbr'
used in the AES Brazil Convention (see credits below). It contains 
the following nine files:

The LaTeX class `aeslac', version 1.0, distributed in
March 08, 2011, contains the following ten files:

readme.txt      --  The file you are reading
manifest.txt    --  The list of files
aeslac.cls      --  LaTeX2e class file
aeslac.cfg      --  aesbr class configuration file
aeslogo.pdf     --  AES logo (PDF)
aeslogo.eps     --  AES logo (EPS)
template.tex    --  A template file
bib.bib         --  Bibtex file used in template.tex
aes.bst         --  AES bibliography style file
template.pdf    --  Compiled template with ``pdflatex''

2. Installation
===============

Before installation you should know where LaTeX's root directory is.
This root directory is where all files used by TeX and LaTeX are stored.
Its name is "texmf". If this terminology does not make sense to you,
seek assistance from a friend or colleague.

Installation procedure:
   a) Copy the files "aeslac.cls", "aeslac.cfg",
      "aeslogo.pdf" and "aeslogo.eps" to a folder
      in the path of LaTeX (where your TeX looks for
      inputs, e.g., "texmf/tex/latex/aesbr/");
   b) Update the TeX file database.
      NOTE: If you are using teTeX, you can do this
      running "texhash" on your terminal. If you use
      MikTeX you can refresh the filename database
      either through the graphical interface or by
      running "initexmf -u".

   ALTERNATIVELY
   a') Copy the files listed above to some folder and load
       them using its relative path. For example, write
       \documentclass{./aesbr} if the class file and
       the main .tex file are in the same folder, or
       \documentclass{../foo/aesbr}, if the class file
       is in the folder "foo" one level above that of
       the main .tex file.

Don't forget to update the (La)TeX file database.

3. Running the template
=======================
Put the files "template.tex" and "bib.bib" in the same
folder. Then, run
  latex template
  bibtex template
  latex template

4. General Guidelines to Authors
================================

* Use "\RequirePackage{...}" instead of "\usepackage{...}".
* Define new commands using \newcommand instead of \def.

5. Contacting us
================
As always, bug-reports, questions, comments, suggestions or
complaints are welcome. Please send them to 
elopez@fing.edu.uy with subject: "aeslac class". Bug reports must be
sent with source and log files.

+---------------------------+
|          README           |
|           FILE            | 
|         aesbr.cls         |
|       (version 1.0c)      |
|         2009.01.26        |
|                           |
|      Sálvio M. Soares     |
|     sallvio@gmail.com     |
+---------------------------+
