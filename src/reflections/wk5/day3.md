# In simple terms what is a sub-document?

A subdocument is another schema model that can be used to store like data about the ouser or object of an upper level document. E.G the the top level document could contain name information about the user of a game... while the the sub-document could contain the player moves. 

# When might you use a sub-document?

It is a neater organization of information and helps get to the pertenent iformation that you might want changed. The sub document could be updated and saved without touching the top -level document.

# How do you add to a collection of sub-documents? What about editing them?
You would create an array in the top-level document with links to all sub-documents. They can be edited directly without changing the top-level document.

Created for Evening challeng:  Created Music API   containing Music Keys, chords, scales.... boriswart.github.io/music.