# Publishing Walking
The purpose of this project is to craft a pathway from valid TEI XML markup through to a high-quality typesetting of _Walking_ by Henry David Thoreau for physical publication.

Publishing _Walking_ will act as a prototype and proof of concept for a workflow that can be applied to other texts.

Overall, the workflow aims for accessibility, so that it can be a foundation for more complicated projects. My rough idea is as follows:\
(1) Obtain a legal, copy-right free plain-text version of the text for publication\
(2) Compile references needed for project, such as reference images to help with typesetting, or other sources if the publication is to include notes and essays.\
(3) Markup the text using XML (Exstensible Markup language), using the TEI (Text Encoding Initiative) schema.\
(4) Write a python Script to help convert the text to as simple LaTex markup.\
(5) Map out a tree of more complicated customisation options for LaTex so that the text can be presented in different ways.\
(6) Add the scripts and codes into a bank of templates that help to streamline future publications.\
(7) Write a rigorous documentation so that the above process is replicable, and can also be used by those who have little experience, but are willing to learn more.

## Why it begins with XML
Markup in XML, and the TEI schema in particular, has the benefit of clarity and a fully descriptive markup, and it encourages exposition. Things like the manuscript description abilities of TEI XML are hugely important typesetting alone, and only become more so if editorial comments or essays are undertaken. An immediate example that comes to mind in _Walking_ is the use of the *,-* punctuation, a period-idiosyncracy that, if preserved, adds charm to the text and allows a more accurate reading - but it has to be rendered sensitively in the typesetting for this to be achieved. It can easily be imagined that rendering tags and information in ther TEI header could help with this and many other similar challenges.

## Where it will end up
The typesetting will be done using TeX or LaTeX. A benefit of typesetting with TeX is that almost everyone can replicated the process for free.

## Why a workflow is necesary
This project aims to explore and ultimately implement custom-written codes in Python programming language rather than using tools like XLST and OxGarage. The former is highly dependent on XML parsing software, and the latter creates an overly complicated typesetting without embracing customisation of the process.

In doing this project I am backing the idea that a workflow using free open-source software can be well-crafted and well-documented such that it opens accessibility to more people. One result of this idea will be the elimination of assumptions. It will not be assumed that the people interested in replicating the workflow have a certain paid-software, or a particular programming knowledge. Instead, I will take people on the journey that I will have to go on to complete this project, linking the resources and writing the explanations necessary to ensure robustness and replicability. I hope that the only assumption that remains will be the ability to put time and effort into carefully reading, comprehending, and practicing.
