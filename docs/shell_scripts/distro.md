the distro shell takes your results.txt and moves it to any potential directory.

ken@DiamondDogs:~/Documents/pickleball/scripts/prod$ ./distro.sh 
Appended results.txt to prevresults.txt
Copying to /home/ken/Documents/pickleball/scripts/mens
Copying to /home/ken/Documents/pickleball/scripts/womens
Copying to /home/ken/Documents/pickleball/scripts/mixed
Copying to /home/ken/Documents/pickleball/scripts/sandbox
Done.


and appends the results.txt to the bottom of prevresults.txt.
prevresults.txt can be used to replay every match if the system
is rebuilt.  Or you decide to throw out a match played in the past.

don't run distro twice!
