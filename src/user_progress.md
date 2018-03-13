# Keeping track of progress

When a student runs a program that solved a particular task, the name of
the world in the html selector changes and displays an additional checkmark
and a robot face emoji: ✓🤖. Note that the look of the robot face emoji
depends on the browser used.

This information is saved in the browser's local storage together with
the programming mode being used (blockly, Javascript or Python); solutions
created using Python's REPL are not saved. The information saved includes
the name of the world, the world collection/menu and the actual code (or
block configuration) used, including the code in the library when using Python.

When students work independently, they may write solutions for many different
worlds. If they wish to show a given solution to a teacher, they can do so
as follows:
in the "Additional options" window, there is an option ("Retrieve solution") to
copy any solution saved for a given world from the browser's local storage
into the programming editor (including the library for Python); this will
replace any code (or blocks) already present in the editors.

In addition, if a student uses two computers (for example, one in a classroom
and the other at home), he or she can **save** the information stored in
a given browser about the tasks solved and import it into another browser,
using the appropriate "save/import" buttons in the "Additional options" window.

Note that the location of the file saved will depend on the browser and
the operating system. For example, using Windows and Chrome, the student will
normally be given a choice as to where to save the file. Using Windows and
Firefox, the file will normally be saved directly into a default location.