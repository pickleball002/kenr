I'm not sure why I thought of this but processing an age change could be a thing.

At this point I'd say   \
Create a new entry, with new age.  (duplicate with fewer games already tossed out).

ken@DiamondDogs:~/Documents/pickleball/scripts/sandbox$ grep Mike origplayers \
Mike,4.0,0,0,0,0.00000,0.00000,4.0,m,19 \
Mike,4.0,0,0,0,0.00000,0.00000,4.0,m,65

age division directories should be recoded

       if ($age > $md65players{$key}->{age}) {
            logprint("Duplicate found for $name — keeping entry with greater age\n");


If a player has no matches played it should take the first one.

But if they have no matches played (again looks in 'players' directory in prod not \
origplayers) then just remove the 19+ entry.    got it?
