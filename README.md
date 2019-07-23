# SEFactionClean
This program clears the Sandbox.sbc for removed player references in factions. 
It's looking for player referenses in "AllPlayersData/dictionary".
Players should be removed first by Torch Essentials. Example: !identity purge 14 (removes players not logged in for 14 days) 

WARNING: Make sure your server is NOT running before applying changes. Always backup the original Sandbox.sbc file.

Cleans:
- MyObjectBuilder_Faction
- MyObjectBuilder_FactionMember
- Factions/Players/dictionary
- Factions/Relations
- Identities/MyObjectBuilder_Identity
- Gps/dictonary
- Factions/Requests/MyObjectBuilder_FactionRequests
- MyObjectBuilder_SessionComponent xsi:type="MyObjectBuilder_SessionComponentContainerDropSystem"/Playerdata
- Research 
