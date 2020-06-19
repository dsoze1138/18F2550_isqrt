# PIC18F2550 calculate integer square root
==========================================

This is a MPLABX v5.40 sample project to show a pic-as(v2.20) 
project and debug method that mostly works.

The method is tedious to use and can become confused if a
step is missed or the wrong tool bar gadget is clicked.

The method goes like this:

Create a "normal" project to develop the code with.
 
Do all the work to get a clean build ready for debug and 
then build it explicitly for debug, without starting a 
debug session.
 
This step needs to be done only once per project:

Create another project using the "File->Import->Hex/ELF...(Prebuilt) File" 
menu to import the ELF file from the "..\dist\default\debug" folder
of the "nornal" project.

Be sure to change the path to where the "debug" project
is created so it is not in the "..\dist\default\debug" path. 
This is important because every thing in this path is deleted 
when the IDE does a clean for the "normal" project.

We can call it the "debug" project.
 
At this point close the "normal" project as the debug session 
will complain that the source files are opened in two projects 
if you do not.
 
Select the "debug" project and start a debug session.
 
Note:
Make sure that you have selected the same "Hardware Tool" 
for program/debug in both projects.

