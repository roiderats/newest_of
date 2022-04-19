The purpose of the script:
Print newest one of files given as arguments (filenames can contain spaces or there's a bug)

Use case:
To open the latest screenshot you took by pressing PrintScreen:
$ gimp $(newest_of ~/Pictures/*)

Usage: newest_of [-y] FILE [FILE [FILE]]...
Print out latest modified filename of bunch of filenames
  -y, --yes  Don't ask for confirmation
  FILE       Everything is a file

