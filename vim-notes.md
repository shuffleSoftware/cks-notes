:vs myfile vertical 
:sp myfile horizontal 

:tabnew new
:tabn next
:tabc close

ctrl + ww : next pane


capture output in a new tab
# Source - https://stackoverflow.com/a
# Posted by Ingo Karkat
# Retrieved 2025-11-19, License - CC BY-SA 4.0

:new | 0read !{bash-command}

g~~ upper>lower<upper

ZZ save and exit
