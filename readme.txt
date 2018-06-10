UPDATE: please use this plugin http://sourceforge.net/projects/npppythonscript/files/

==Installation==

1. Copy contents of this archive into Notepad++ 'plugins' folder (basically, it's C:\Program Files\Notepad++\plugins\)
2. Restart Notepad++

You should see "Zen Coding" menu item in top menu.
If you don't see this item or plugin doesn't work, try to install latest Windows Scripting Host: 

http://www.microsoft.com/downloads/details.aspx?FamilyId=01592C48-207D-4BE1-8A76-1C4099D7BBB9&displaylang=en


==Changing settings and shortcuts==

You can find Zen Coding settings near the top of the includes/Zen Coding.js file and shortcut settings
at the very bottom of it.


==Kudos==

Zen Coding for Notepad++ is based on NppScripting plugin by sieukrem:
http://www.softwarecanoe.de/data/nppscripting.zip

This plugin allows you to extend Notepad++ with JavaScript. You can write your own scripts and put them
in 'includes' folder of this plugin.

More info (in Russian):
http://sieukrem.habrahabr.ru/blog/86626/

==Known issues in v0.7==

I don't know how to write up and down key codes in order to make increment/decrement 
number action useful so I commented them out. Also, looks like CSS parsing doesn't
work with WSH so I have to investigate this problem.

Anyway, I think it will be the last release of Zen Coding for NP++ as JS plugin,
users should switch to Python version: http://sourceforge.net/projects/npppythonscript/files/ 