# Usage : 
Mikrotik is implementing goto's (jump action).
Basicaly, you create multiple chains that can jump to another chain. You create a chain per peer to set preferences for said peer and then redirect to your more generic filter lists.
After it has run the entire chain it has gone to, it goes back into the originating chain.

