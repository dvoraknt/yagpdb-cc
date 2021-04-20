**What is this?**
This is modified version of the existing starboard custom command in the /fun/ folder. Several large changes have been made and more setup is required, 
this command now consists of two separate CC's that must be used simultaneously. The first command is the basic starboard, the second is a starboard channel listener. 

**Features added my me** (some basic features have been added to the other starboard command)
-posts automatically removed when they fall below set star threshold or when number of anti-stars has been reached
-ability to ignore stars/ant-stars on old posts (server customizable)
-anti-star feature similar to an upvote/downvote system with customizable threshold for 'downvotes' before autodeleting (server customizable)
-ability to react directly on posts in your #starboard channel with either star or anti-star
   -accurate tracking between original post and starboard post
   -users are unable to duplicate stars/anti-stars between channels
 -reactions from the original message poster can be ignored (server customizable)
 -message warnings for attempts to duplicate stars/anti-stars and self stars (server customizable)
 ***NOTE: not all of these features will work on starboard messages created with the original starboard cc***
 
 **SETUP:**
 1. Add both custom commands to your server with trigger 'Reaction - Added + Removed reactions'
 2. starboard.go.tmpl **MUST** be set to **IGNORE* your starboard channel
 3. starboardListener.go.tmpl **MUST** be set to work **ONLY** in your starboard channel
 4. **user configured variables MUST be the same between both commands.** If you change something on one be sure to change it on the other
    -don't forget to configure your starboard channel ID and desired emojis for basic functions to work
    
**Why did I make this?**
Starboard holds a special place in my heart on discord and I want a starboard with what I perceive to be the most important and valuable features.
Every starboard bot seems to have one feature or another but none have them all, I want this to be that one.

**Why is there no star leaderboard?**
I don't like it personally. My history with starboard is that funny or out of context comments, self made memes, etc get starred. Having a leaderboard 
encourages members to make low effort or attention seeking posts for easy stars. It's better when it's organic in my opinion.
    
**Known Issues**
None that I know of. I've done my best to squash all bugs I could find and fix any inconsistencies. I've tested a wide range of situations but surely not all,
if you have a problem I can be contacted on discord through the official YAG server at DV0RAK#0001.

HUGE THANKS to joe for creating the base code in this custom command, another huge thanks to satty whose giveaway code provided the inspiration and assistance
needed for some of the code in here. Some more thanks to the bois and gals in the cc-help channel for answering some questions and the years long backlog of 
messages that I leeched off of.
