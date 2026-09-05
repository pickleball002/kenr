A new switch option in the clean scripts.

#!/bin/bash
# take deviation output, clean the blacklist
# save as csv for the make script
# run after superdistro

grep -vi -f blacklist.list deviation > tempcsv

cat sqltopper tempcsv > deviation.csv

./make_overall.pl --gpm 1

This looks at the current month and figures out how many games one must play for their name to appear.

It's September and with --gpm 1 set you must have played 9 games by end of month for your name to appear.

does not effect standings, only appearance
