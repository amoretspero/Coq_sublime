# Coq_sublime

# Systax : 

Thanks to http://fsharp.github.io/fsharpbinding, the fsharp binding project.

Since Coq's syntax is somewhat similar to OCaml and F#(which has taken many syntax of OCaml),

I used to modify the F# Sublime_text syntax file to deal with Coq.

When all modification is done, new syntax file will be uploaded just for Coq!

Usage :

Run ST2 and go to Preferences -> Browse Packages

Copy the folder 'Coq'(it is in Syntax folder.) there.

Restart ST2.

# SublimeREPL :

Thanks to wuub (https://github.com/wuub/SublimeREPL), who has developed wonderful REPL for so many languages

In Sublime_REPL folder, two files are included for using coqtop.exe for REPL in Sublime Text.

If have questions with using SublimeREPL, please visit link above.

Usage :

Install SublimeREPL (Link above.)

Run ST2 and go to Preferences -> Browse Packages

Go to SublimeREPL/config folder.

Copy the folder 'Coq'(it is in Sublime_REPL folder.) there.

Restart ST2.

# Build :

This makes build activity for coq files(.v) in Sublime Text. (Currently only for ST2)

Usage :

You need to install Coq first.

And Go to "Control Panel -> System -> Advanced"

Click "Environment Variable"

Modify 'Path' variable, by adding the location of coqc.exe with semi-colon in front of it. (EX : blahblah;~~/bin)

Paste the .sublime-build file into Sublime Text 2's Pristine Package/User folder.

Restart and use with Ctrl + B


