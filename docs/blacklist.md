The blacklist.list are a list of names to not be included in a rollup.

I don't recommend \
Randa \
Rando \
These are used for ranking purposes only \

A private group \
My first private group I prefaced all names with "T1" so I'll exclude all T1 starting names

People just don't want to see their name in public....it's going to happen.

The superdistro file will push 'blacklist.list' to all directories each time.   So it needs to be only \
listed once in /prod

grep -vi -f blacklist.list deviation > tempcsv

This take my deviation file from /prod    \
(rank by change, not by highest rating)

cat an sqltopper above it and rename to .csv for publishing

