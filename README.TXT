similar.exe is program designed to test the similarity of any two UCI
chess programs.    

It is a program designed to be run from a command shell.  It is not a
graphical utility.

When the program is run a data file is created in the working
directory.  Because of this, the program should always be run from the
same directory.

Invoke the program with no arguments to get usage - and also a catalog
of all programs measured.   

To add data from a new program called "myChessProgram", run it like
this:

    similar.exe -t myChessProgram

This assumes "myChessProgram" is in the PATH and can be executed and is
a UCI chess program.

The program can be run at different times which can be specified in
milliseconds.  The default is 100 which is 1/10 of a second per
position.  However, we could run it at 1/2 second like this:

    similar.exe -t myChessProgram 500

To get a report, you must specify a program to be reported on by id.  When
you run the program without command line arguments you will get a list of
all programs with their "id" on the left column:

  1) Komodo64 1.2 JA (time: 100 ms)
  2) RobboLito version 0.084 (time: 100 ms)
  3) Houdini 1.5 w32 (time: 100 ms)

So to report on RobboLito, do this:

   similar.exe -r 2







