# LaTeX - Letter Template
## Disclaimer
By no means this letter template has been invented all by myself. Contrary, it is based on the examples within the KOMA-Script documentation, provided by Markus Kohm on his website (https://komascript.de).
Packages used in these examples might be obsolete by now. I'll probably update them in the future. For now, these versions are still working well for me.
Presently the examples are in German only, English versions will be added later.

## How to use
### Main files
All templates use the scrlttr2 class from the KOMA-Script.

The ***LetterTemplate_mwe.tex*** is a minimum working example. Try this at first to see if your LaTeX system compiles without errors. This example natively uses English (check the month in the output file). If you would like to use it in a different language, you have to load the respective packages.

The ***LetterTemplate.tex*** is a full working template (at least on my machine...) containing not only some adjustments but also various extra parameters and external files. Nothing too fancy, though.

### Auxiliary files
There are three '''.lco''' files. In my case is use them to setup mainly variables.
***absender.lco*** defines variables used by scrlttr2 to set adresses, phone numbers etc.

To use these templates check for the relevant parts in the tex-files and replace the examples with your information.
