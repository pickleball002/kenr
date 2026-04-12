
results.txt is a batch results file in the following format

n,kennyz,BobY,karenx,JoshQ,1

the first field is called 'GrandPrix'.   Would you like the results doubled for this match?   To be used for special occassions, playoffs...
name of first winning player
name of partner
name of losing player
name of losing partner
number of games played

the names must match exactly.   In the above example if there is one 'kenny' you will be okay.   If there is more than 1 'kenny' would fail

once results.txt is updated (maybe one time at the end of a weekend, there could be many records in one file) You can run the file
for prod, mens, womens and mixed directories.   Looking at the data above it won't update any directory but 'prod' because it's one
female player in a game of three men.   But if you did run it no harm is done.
