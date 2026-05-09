
ken@DiamondDogs:~/Documents/pickleball/scripts/prod$ ./rebuild.sh \
=== REBUILD PROCESS STARTING === \
'prevresults.txt' -> 'results.txt' \
Resetting mens directory \
'origplayers' -> 'mdplayers' \
Resetting womens directory \
'origplayers' -> 'wdplayers' \
Resetting mixed directory \
'origplayers' -> 'mxplayers' \
Resetting sandbox directory \
'origplayers' -> 'players' \
=== REBUILD COMPLETE === 


ken@DiamondDogs:~/Documents/pickleball/scripts/prod$ ./distro.sh \
Appended results.txt to prevresults.txt \
Copying to /home/ken/Documents/pickleball/scripts/mens \
Copying to /home/ken/Documents/pickleball/scripts/womens \
Copying to /home/ken/Documents/pickleball/scripts/mixed \
Copying to /home/ken/Documents/pickleball/scripts/sandbox \
Done.

ken@DiamondDogs:~/Documents/pickleball/scripts/prod$ ls -lart prevresults.txt results.txt \
-rw-rw-r-- 1 ken ken 2612 Apr  9 12:17 results.txt \
-rw-rw-r-- 1 ken ken 2612 Apr  9 12:19 prevresults.txt \
ken@DiamondDogs:~/Documents/pickleball/scripts/prod$ 


ken@DiamondDogs:~/Documents/pickleball/scripts/prod$ ./batch.sh results.txt


ken@DiamondDogs:~/Documents/pickleball/scripts/prod$ !2099
grep -i FAILURE logging \
BATCHINPUTFAILURE: n,Victor,kevinino,Samiam,youngJohn,1 \
BATCHINPUTFAILURE: n,Raman,vinay,shaunh,carmelo,1

cd to ../sandbox and run /thescript to find the error \

=== Creating Backup File: backupplayers ===

=== First Pair Input ===
Enter first name: victor

No exact match for 'victor'. Possible matches:
  1) VictorJ
  2) VictorV
Select a number: 

ken@DiamondDogs:~/Documents/pickleball/scripts/documentation$
