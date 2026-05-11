I think the question I'm asked most frequently is

'What is your algorithm?'   It's a curious question.  

What answer could I give in 25 words or less 
that would make any sense?   Maybe this is the community shouting out that an existing algorithm is not 
liked.

Someone's 'Claude' recently trawled my page and pulled out keywords like 'invert' or 'reliability' but
might miss some general concepts that would answer this question better.

(Although I tentatively called this project 'Enterprise rating' perhaps a better analysis
would be 'local DUPR'.   Points for Claude.)

The algorithm is based on two parts.  Both completely mathematical ideas that I made up.
After each part there are some sub topics which you may or may not agree with it, but they
are mine.

Part I.

I believe that two 4.0s against two 4.0s is an equal match up.  No favorite.
So next I conclude that a 4.1 and a 4.0 would be the favorite against two 4.0s.
Then finally a 4.1 and a 3.9 would be an equal match up against two 4.0s.
(This gets tricky as it stretches.  Are a 4.5 and a 3.5 the same as two 4.0s?
Did they stack?   Can the 4.5 take enough shots?   Since it's not an obvious answer
we'll just say again they are equal).  

The 4.1 and 4.0 are 8.1 total the two 4.0s are 8.  So now if the favorite wins
they win less of the ratio (8/8.1) and if the underdog wins it's a bigger slice of
the pie (8.1/8).   More later.

I.A

At some point the match up becomes a little one sided.   If two teams are favored \
by more than .55 (say 4.28 and 4.31 against 4.0 and 4.0) then there is a .56 bump. \
In short if the favorite wins, they win less.   If the underdog wins they win more. 

Remember winners always move up and losers move down.

Part II.

How many games would someone have to lose as a 4.1 to move to a 4.0 with essentially
playing equal weight opponents?  If you went to a tournament an lose 11-7 11-7.  Then in 
consolation lost 15-10.   That's not enough to move a .1 needle.
Second tournament same result.  So that's about right.   Losing 6 games or as a 4.1 with
same opponents is about the amount needed to move you to 4.0.

There are lots of sub topics here....

II.A - Reliability timeline

When the program fires up with no matches played by default you have 33 games in every
division to satisfy reliability.  This number is configurable!   In other words the value
from Part I and Part II is added or subtracted from your rating.   After 33 games this value
is cut in half.  This is enough time for you to get a somewhat reliable rating.   But you
might be playing against people that are just starting and have played less than 33 games.
While they move up and down, you will move at half the pace.   (Maybe someone entered as
a 3.0 that should have been a 4.0....).   

This reverts back at the 51 game mark when all players hit 51 games.   In other words once
everyone has a pretty reliable rating, points are doubled up again!









