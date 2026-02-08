# JellyCacheIDK
BaseItemRepository.cs is the version as is from jellyfin-10.11.6.zip of the official Jellyfin.Server Project, NEW_BaseItemRepository.cs is the one with changes if you want to compare or compile yourself.
  
Jellyfin.Server.Implementations.dll is the compiled version with the changes.  
  
Step 1. Stop Jellyfin  
Step 2. Go to Jellyfin/Server and PLEASE MAKE A BACKUP OF YOUR EXISTING Jellyfin.Server.Implementations.dll DON'T DELETE IT. In case there is a bug or something, simply replace it again.  
Step 3. Replace Jellyfin.Server.Implementations.dll with my version (you only need the .dll file, the two .cs are only to show the differences).  
Step 4. Start Jellyfin  
  
WARNING: THE NEW LINES/CHANGES ARE AI/LLM/GPT GENERATED I ONLY GAVE THE IDEAS AND INSULTED IT WHEN SOMETHING DIDN'T WORK, IT SEEMS TO WORK ON MY SET UP WHICH DOES NOT MEAN THIS IS "PERFECT" OR BY ANY MEANS PRODUCTION LEVEL CODE, I HAVE NO CLUE WHAT I'M DOING. USE AT YOUR OWN RISK.  
  
The idea was to add a cache layer so every query gets cached and the long load times happen only on first visit FOR SOME REASON, it works right away which should take time, but it doesn't? It makes no sense. But it's fast and i haven't seen anything breaking yet lol  
  
