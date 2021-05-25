# LaTeX - Letter Template
## What is this?
This repository contains templates for the creation of letters with the LaTeX typesetting system. You will need a fully working TeX system on your computer to make use of them. TeX Live (http://www.tug.org/texlive/) and MacTeX (http://www.tug.org/mactex/) are widespread, but ot hte only distributions.
If you have no idea at all what this is about check out the wikipedia (https://en.wikipedia.org/wiki/TeX). If you do, you probably know where to look.

## Disclaimer
By no means these letter templates have been invented all by myself. Contrary, it is almost exclusively based on the document classes and examples from the KOMA-Script environment, provided by Markus Kohm on his website (https://komascript.de).
I know, some packages used in these examples are obsolete by now. I'll probably update them in the future. For now, these versions are still working well for me.
Presently the examples are in German only, English versions will be added later.

## Description

### Main files
All templates use the scrlttr2 class from the KOMA-Script.

The [***LetterTemplate_mwe.tex***](https://github.com/mrchanceluss/LaTeX/blob/main/LetterTemplate/LetterTemplate_mwe.tex) is a minimum working example. Try this at first to see if your LaTeX system compiles without errors. This example natively uses English (check the month in the output file). If you would like to use it in a different language, you have to load the respective packages.

The [***LetterTemplate.tex***](https://github.com/mrchanceluss/LaTeX/blob/main/LetterTemplate/LetterTemplate.tex) is a full working template (at least on my machine...) containing not only some adjustments but also various extra parameters and external files. Nothing too fancy, though.

### Auxiliary files
#### What files are there?
There are three '''.lco''' files. I use them to setup variables containing information like phone numbers and addresses.

***absender.lco*** defines variables used by scrlttr2 to set adresses, phone numbers etc. for the sender.

***fusszeile.lco***
