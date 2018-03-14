The list in this folder has been compiled using a search spider 
that finds porn spam bots spamming city name hashtags, like #Mönchengladbach 
or #Viersen.

The "kiss69.me" operators target multiple languages and countries with
distinct clusters of bot accounts, about 400-500 per language per 
my current analysis. 

The format is compatible with Twitter's block-list import/export format
and uses UserIDs. To see the respective profile, use 
`https://twitter.com/intent/user?user_id={id}` for a listed ID.

Please mind that the Twitter import function for block lists is VERY picky and 
will expect LF line endings and that the last line must not be blank. The ZIP file 
contains a version of the block list that will work for import.

Get the ZIP file directly from [this link](https://raw.githubusercontent.com/clemensv/twitter_spamlists/master/block-kiss69-me.csv), 
unpack the file on your PC, and then go to your [block list on Twitter](https://twitter.com/settings/blocked) 
and choose the Options dropdown on the right hand side above the list to import.
