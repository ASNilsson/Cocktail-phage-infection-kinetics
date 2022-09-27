Cocktail program version 2.3.4 9/20/2022

Installation notes
------------------

Installation: No special installation software is necessary, just unpack the content
of the Zip folder into a new folder, place it where you want it, and name it "Cocktail".
The folder should contain:
Coctail.exe, a Windows 64-bit executable file.
Readme.txt, this file
Cocktail.pdf, information file
Three Cocktail data example files: Abedon_2009_Fig_2F.ctl, Lenski_1988_Fig_2a.ctl,
Lenski_1988_Fig_2b.ctl and Fig_2_demo.ctl

The program can be runned with on-screen user input or by loading a data file.
To establish the link between .ctl data files and the program, 1. Run the program once.
2. Click a .ctl file. 3. In the "Open this file with" menu, scroll down to "Cocktail", 
check the box "Always use this program..." and press OK. 
The program and the associated file type .ctl are now added to the Windows registry.
(No need for an installer program to do this simple operation).

The program
-----------

The Cocktail program models the dynamics of one or two bacteriophages infecting bacteria
in a chemostat. The Cocktail 2.3.4 is a beta version. Please let me know if there are
issues or bugs. Although I have done my best to assure that it works, it may contain 
errors. If you think you have spotted an error, send me an email at: anders.s.nilsson@su.se,
and include the .ctl file causing the crash / unwanted / erroneous behaviour of the program.
Full contact details can be found by left double-clicking somewhere else than in input 
boxes in the program input window.

The program can be run on Windows 64-bit systems. It is in English, but some instructions
may turn up in the language set on your computer when Windows DLLs are called (file dialogs).
It was developed with Object Pascal from the Free Pascal Team (Free Pascal: A 32, 64 and 16 
bit professional Pascal compiler. Version 3.2.0. URL https://www.freepascal.org. 
RRID:SCR_014360), using the Lazarus IDE and libraries developed by the Lazarus Team, 
(Lazarus: The professional Free Pascal RAD IDE. Version 2.0.10. URL http://www.lazarus-ide.org.
RRID:SCR_014362). The IDE, compiler and program libraries can be downloaded from: 
https://www.lazarus-ide.org/index.php?page=downloads. Developing programs with Lazarus is quick
and easy. Lazarus is an Object Pascal extension of Borland's Delphi (presently distributed by
Embarcadero Technologies).

The .ctl file
-------------

The results of the program can be saved as charts, in PNG or SVG graphics file formats, or
as a .ctl data file. The items in the .ctl file constitute the complete settings for running
the program. The format is a plain .txt file but note that the format is fixed. Moving 
items to another position in the file will inevitably result in a file error. A comma (,)
is used as a delimiter when more than one item is to be found on a line. Omitting that 
comma, or using another delimiter, will also result in a file error. Editing a .ctl file that 
works as a template, and save it under a new name, is a good idea.

Advice on use
-------------

Infection dynamics is complex. The results are often difficult, and sometimes counterintuitive,
to explain. When running a case, try not to change variables randomly but in a systematic way
and not all variables at the same time, e.g. keep all but one parameter constant and change just
one variable at a time. Also, start simple with known parameter settings and one bacteriophage
only.

Licence information
-------------------

The Cocktail program is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike
4.0 International License. To view a copy of this license, visit 
https://creativecommons.org/licenses/by-nc-sa/4.0/ or send a letter to Creative Commons, 
PO Box 1866, Mountain View, CA 94042, USA. Feel free to modify the program adding / modifying 
functions. Commercialisation is not allowed. The source code for the Cocktail program is available
from me on request by email or from the journal website where the article decribing the program is
published. If you benefit from the program, a donation to Médecins Sans Frontières would be 
appreciated: https://www.msf.org/donate

Disclaimer
----------

The Cocktail program is based on established mathematical models and extension thereof but, 
as with all models, it only represents a fraction of reality. Users of the program should be 
aware of that the program results are approximations and are asked to check results by means 
of own calculations.The main purpose of the program is to generate hypotheses about bacteriophage 
infection dynamics that can be experimentally tested.  I disclaim any responsibility for results 
generated for other purposes. Stockholm 10/09/2022 Anders.S.Nilsson, anders.s.nilsson@su.se.
