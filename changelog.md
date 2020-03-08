# Changelog

## Update 0.2.2 - Research update

💠 **NEWS** 💠 
- Logic of the main process segmented into smaller logical parts  
- Add reset profile command  
- Gamesales command now allows mentioning a different author  
- Guild customizable gamesales  
- Role related commands moved to RoleModule  
- GuildModerationModule grouped to categories  
- UserModerationModule grouped to categories  
- Command Help - fixed command searching -&gt; highest hierarchy rank being propagated  
- Introduced online ManagerBot documentation  
- Reworked output of not enough permission - added required rank  
- HelpModule - Add maybe you meant clues when wrong command name is inserted  
- HelpModule - Order commands ascending and highlight sub-category commands  
- Server customizable afk settings  
- Automatically add leveling role when user doesn't have one  

💮 **BUG FIXES** 💮 
- Gamesales url validation error  
- Empty embed error  
- UserLeftGuild logging error  
- Testing mode error  
- Showing bot profile prevented  
- Rejoin guild and get previous data fixed  
- Help command output fixed  
- Cryptomodule not showing bug fixed  
- Command weather bug fixed  
- Profile showing bug fixed  
- Promoting/Demoting user moderation role  
- Logging wrong commands output fixed  
- Maximal rank adding playtime bug fixed  
   
✔️ **COMING SOON** ✔️ 
- Economy system  
- Shop  
- Rework saving data - use DB  
- Bot's Website  
- Separation of Core and UI  
- Unit testing  





## Update 0.2.3 - Database update

💎 **NEWS** 💎
- Data saving changed, moved from JSON to Database storage
- SelfAssignableRoles - Syntax refactoring
- Command outputs refactored
- Refactored entity indexing
- Created multiple configurations for bot
- Created separate testing environment
- Command grouping into categories, that are highlighted in help
- Add editing of welcome gate
- Add showing of default messages and gamesales settings
- Profile generating optimized - speed increased 3 times
- Audit values output refactored
- Add autonomous DJ role assigning
- Add pipeline for bot management
- Add automated unit tests

🐛 **BUG FIXES** 🐛
- Fixed not assigning DJ role automatically
- Fixed DJSettings showing
- Fixed bug when setting afk channel
- Fixed bug while checking user leveling role
- Fixed bug when command not found
- Fixed bug when reaction message was not found
- Fixed bug in role adding permissions
- Fixed bug in sending empty message when user left server
- Fixed bug when showing communication channels
- Fixed bug when changing nickname
- Fixed bug in adding playtime
- Fixed bug while closing and claiming reports
- Fixed bug in generating profile
- Fixed bug in removing warnings





## Update 0.2.4 - Activity Update

✏️ **NEWS** ✏️
- /role command now shows a list of selfassignable roles
- Added activity showing - daily, weekly, monthly. Command: /activity <daily/weekly/monthly>
- Added command to show or to remove reports
- Refactored storing of profile images
- Added yes/no emoji storing
- Enhanced voting system
- Added Game Activity Vizualization in /activity

🧯 BUG FIXES 🧯
- Bug fixed when output description is empty
- Bug fixed - /topusers did not show playtime according to the actual playtime
- Bug fixed - AFK channel
- Bug fixed - wrong help showing, duplicite names
- Bug fixed - roles
- Bug fixed - /requestmute
- Bug fixed - profile image dont generate after nickname reset
- Bug fixed - specific nicknames were not saved into the DB
- Bug fixed - /afk enable and disable





## UPDATE 0.2.5 - Economy UPDATE

🎐 **NEWS** 🎐
- Add shop
- Add guildRoles, customRoles stocked in the shop
- Add shop detail command
- Add possibility for dynamical setting of minimal level for nickname change
- Add new module - User Customization - for customizing user roles
- Add Custom role customization
- Add Showing User custom roles

💥 **BUG FIXES** 💥
- Fixed bug when adding Guest role without accepting the rules
- Fixed wrong command names
- Fixed help bug - not ignoring case sensitivity
- Fixed bug with renaming all user accounts when bot joins server
- Fixed afk warn bug
- Fixed command descriptions
- Fixed bug for checking when user is in a Voice Channel
- Fixed activity chart drawing bugs