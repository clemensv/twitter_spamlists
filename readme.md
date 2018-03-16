IMPORTANT: This is work I am doing for myself because I'm tired of the
spam. I am in no way suggesting or recommending for anyone to use 
these lists. They work for me, you may find them useful. 

This work is shared under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/). 

The list in this folder has been compiled using a search spider 
that finds porn spam bots spamming city name hashtags, like #Mönchengladbach 
or #Viersen as well as "like-spam" from that same group.

The strategy I apply uses a Computer Vision service to verify that included
accounts are posting pictures that are "racy", in addition to at least one
further criterion. The Computer Vision step is skipped if the picture has
already been classified or if the profile shows a pattern known from a spammer
group. The nature of the chosen algorithm will occasionally find candidates
that are not part of the targeted bot farm, but that nevertheless meet the
blocking criteria. Several accounts will look like false positives at first
sight, but at closer inspecting you will find that most of them have timelines
nearly completely consisting of retweets, which this algorithm ignores. It will
rather only look at tweets originating from that account and those will then
have been classified as meeting the criteria. 

The format is compatible with Twitter's block-list import/export format
and uses UserIDs. To see the respective profile, use 
`https://twitter.com/intent/user?user_id={id}` for a listed ID.

Please mind that the Twitter import function for block lists is VERY picky and 
will expect LF line endings and that the last line must not be blank. The ZIP file 
contains a version of the block lists that will definitely work for import.

Get the ZIP file directly from [this link](https://raw.githubusercontent.com/clemensv/twitter_spamlists/master/block-datewith-me1.zip), 
unpack the file on your PC, and then go to your [block list on Twitter](https://twitter.com/settings/blocked) 
and choose the Options drop-down on the right hand side above the list to import.

Twitter has size limits that require me to split this up.

----

Die Liste in diesem Verzeichnis ist von einem automatischen Suchprogramm
erstellt worden, das "Porno" Bots, die Städte-Hashtages wie #Mönchengladback oder #Viersen
vollspammen automatisch findet.

Das Format ist kompatibel mit dem import/export Format von Twitter und 
verwendet numerische Benutzer-IDs. Um das jeweilige Profil zu sehen, 
verwende `https://twitter.com/intent/user?user_id={id}` mit einer 
gelisteten ID.

Die Twitter Import/Export Funktion is sehr anspruchsvoll in Sachen 
Formatierung der Zeilen- und Dateinenden. Die ZIP Datei enthält Dateien, 
die sicher funktionieren.

Lade die ZIP Datei direkt von [diesem Link](https://raw.githubusercontent.com/clemensv/twitter_spamlists/master/block-datewith-me1.zip), 
herunter, packe sie aus, und dann gehe zur [Blockierliste auf Twitter](https://twitter.com/settings/blocked) 
und wähle "Erweiterte Optionen" auf der rechten Seite über der Liste für den Import.

Die Größenbeschränkungen von Twitter für diese Dateien erfordert, dass
ich mehrere Dateien zur Verfügung stelle.


Bitteschön :)
