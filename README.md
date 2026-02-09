# JellyCacheIDK

Updates so far:  
First version had a issue where it couldn't differentiate between Users and two Show libraries. Added UserID and LibraryID to the Cache Key.  
5 Days cache Timeout was too high, lowered it to +3Hours (if hit again) and evict for sure after 24Hours, this should allow for new entries to show up.  

  
Step 1. Stop Jellyfin  
Step 2. Go to Jellyfin/Server and PLEASE MAKE A BACKUP OF YOUR EXISTING Jellyfin.Server.Implementations.dll. In case there is a bug or something, simply replace it again.  
Step 3. Replace Jellyfin.Server.Implementations.dll with my version (you only need the .dll file).  
Step 4. Start Jellyfin  
  
WARNING: THE NEW LINES/CHANGES ARE AI/LLM/GPT GENERATED I ONLY GAVE THE IDEAS AND INSULTED IT WHEN SOMETHING DIDN'T WORK, IT SEEMS TO WORK ON MY SET UP WHICH DOES NOT MEAN THIS IS "PERFECT" OR BY ANY MEANS PRODUCTION LEVEL CODE, I HAVE NO CLUE WHAT I'M DOING. USE AT YOUR OWN RISK.  
  
The idea was to add a cache layer so every query gets cached and the long load times happen only on first visit, FOR SOME REASON it works right away which should take time, but it doesn't? It makes no sense. But it's fast and i haven't seen anything breaking yet lol  
