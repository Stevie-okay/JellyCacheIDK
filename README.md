# JellyCacheIDK
  
Update:  
"AncestorIds" this one seems to be the culprit of all. If this flag is allowed through all hell breaks lose.  
In V0.6 i tried to only disable this flag (few exceptions since there are sooo many flags).  
  
    
Step 1. Stop Jellyfin  
Step 2. Go to Jellyfin/Server and make a backup of your existing Jellyfin.Server.Implementations.dll. In case there is a bug or something, simply replace it again.  
Step 3. Replace Jellyfin.Server.Implementations.dll with my version (you only need the .dll file).  
Step 4. Put cache-flags.txt inside the Jellyfin/Serve too.  
Step 4. Start Jellyfin  
  
WARNING: THE NEW LINES/CHANGES ARE AI/LLM/GPT GENERATED I ONLY GAVE THE IDEAS AND INSULTED IT WHEN SOMETHING DIDN'T WORK, IT SEEMS TO WORK ON MY SET UP WHICH DOES NOT MEAN THIS IS "PERFECT" OR BY ANY MEANS PRODUCTION LEVEL CODE, I HAVE NO CLUE WHAT I'M DOING. USE AT YOUR OWN RISK.
