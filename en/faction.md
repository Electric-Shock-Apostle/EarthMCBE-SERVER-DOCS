Here is a list of all the Factions commands. They are each explained in further detail later.  
/f ?,h,help [page=1] get help  
/f list [page=1] list all factions  
/f f,faction [faction=you] show faction information  
/f player [player=you] show player information  
/f status [page=1] [faction=you] [sort=time] show status  
/f join <faction> join faction  
/f leave leave your faction  
/f warp use warps  
/f warp go <warp> [faction=you] go to a warp  
/f warp list [faction=you] [page=1] list warps  
/f warp add,create <name> [faction=you] add new warp  
/f warp remove <warp> [faction=you] remove warp  
/f map [on/off=once] show territory map  
/f create,new <name> create new faction  
/f name <new name> [faction=you] set faction name  
/f description <desc> change faction description  
/f motd [new=read] faction motd  
/f sethome [faction=you] set the faction home  
/f unsethome [faction=you] unset faction home  
/f invite manage invites  
/f kick kick player from faction  
/f title [title=none] set player title  
/f rank set <player><rank> set rank  
/f rank show <player> show rank  
/f rank list [page=1][faction=you] list ranks  
/f rank edit edit ranks  
/f rank edit create <name> <priority> [prefix=none] [faction=you] create rank  
/f rank edit delete <rank> [faction=you] delete rank  
/f rank edit name <rank> <new name> [faction=you] set rank name  
/f rank edit prefix <rank> <new prefix> [faction=you] set rank prefix  
/f rank edit priority <rank> <new priority> [faction=you] set rank priority  
/f money manage faction money  
/f money balance [faction=you] show faction money  
/f money deposit <amount> [faction=you] deposit to faction  
/f money withdraw <amount> [faction=you] withdraw from faction  
/f money ff <amount> <faction> <faction> transfer f –> f  
/f money fp <amount> <faction> <player> transfer f –> p  
/f money pf <amount> <player> <faction> transfer p –> f  
/f top <Topcategory> [page=1] show faction top  
/f seeChunk,sc [active=toggle] see the chunk you stand in  
/f seeChunkOld,sco see the chunk you stand in  
/f territorytitles,tt [on|off=toggle] toggle territory titles  
/f claim claim faction territory  
/f unclaim unclaim faction territory  
/f access manage access  
/f relation manage faction relations  
/f perm change faction permissions  
/f flag manage faction flags  
/f unstuck teleport to nearest wilderness  
/f override,admin [on/off=flip] enable override mode  
/f disband [faction=you] disband faction  
/f powerBoost manage powerboost  
/f setpower,sp set power  
/f config edit config  
/f clean clean the factions database  
/f v,version display plugin version  
###### Overview  
The following commands are explained in this section:  
/f Factions basecommand  
/f ?,h,help [page=1] get help  
/f list [page=1] list all factions  
/f top <Topcategory> [page=1] show faction top  
/f f,faction [faction=you] show faction information  
/f player [player=you] show player information  
/f status [page=1] [faction=you] [sort=time] show status  
/f join <faction> join faction  
/f leave leave your faction  
/f map [on/off=once] show territory map  
**When you type /f you get a list of all the Faction related commands. Typing /f ? 2 will get you to the second page. Listing the factions is done by /f list and also here there can be several pages. If you want more than just a list you can see all the top factions in several categories by typing /f top. If you then pick a faction and want to get to know some basic information about it you can type /f f [faction] and if no faction is specified you will get the info about your own faction. Likewise /f player [player] will get you information about a player, and if no player is specified it will be about yourself. To get information about players in a faction you type /f status [page] [faction] here there can be several pages to go through, so specify one if you want to see past page 1, and specify a faction to look at a faction that is not yours.**  
**When a faction invites you to join you do so by typing /f join <faction>. When you want to leave you type /f leave. You can only be member of one faction.**  
**You can see who owns the land around you by typing /f map.**  
###### Warps
The following commands are explained in this section:
/f warp use warps  
/f warp go <warp> [faction=you] go to a warp  
/f warp list [faction=you] [page=1] list warps  
/f warp add,create <name> [faction=you] add new warp  
/f warp remove <warp> [faction=you] remove warp  
**A faction can have warps. To see what warps your faction has type /f warp list. To go to one of the warps type /f warp go <warp>. Everyone with the permission (permissions are covered later) “warp” can use all of a factions warps. If you have the permission “setwarp” then you can add and remove warps for the faction with /f warp add and /f warp remove. There is a max number of warps set by the server admins.**  
###### Creating a faction
The following commands are explained in this section:  
/f create,new <name> create new faction  
/f name <new name> [faction=you] set faction name  
/f description <desc> change faction description  
/f motd [new=read] faction motd  
/f sethome [faction=you] set the faction home  
/f unsethome [faction=you] unset faction home  
**You create a faction by typing /f create <name>. If you want to give it a new name later you type /f name <new name>. You change the public faction desciption with /f desc <desc>. You can view your faction’s Message of the Day by typing /f motd and you can change it by typing /f motd <new motd>. You can even use colour in your motd.**  
**You set your faction home by doing /f sethome when standing where the home should be. You can set a new home by doing /f sethome again, or you can decide to have no home and do /f unsethome (not recommended).**  
###### Member management  
**The following commands are explained in this section:**  
/f invite manage invites  
/f invite list [page=1] [faction=you] list invited players  
/f invite add <player> invite player  
/f invite remove <player/all> revoke an invite  
/f kick kick player from faction  
/f title <player> [title=none] set player title  
**When you want someone to join your faction you do /f invite add <player> you add that player to the list of invited players. When you want to know who you have invited you do /f invite list. Then you might want to remove someone from that list and revoke their invite, you do that by typing /f invite remove <player> and if you want to clear the list entirely you do /f invite remove all.**  
**If someone your faction is misbehaving you can kick them with /f kick <player>.**  
**If someone in your faction is special and deserves a title you do /f title <player> [title]. If you want to remove their title you just leave the title empty and do /f title <player>. You can use colour in your titles.**  
###### Ranks
**All factions have ranks. You start out with Leader (400), Officer (300), Member (200) and Recruit (100), but you can add and remove as you wish. Ranks can also have a prefix that will be prepended before any player name (prefixes, too, can have colour). All ranks have a priority showed in parentheses after the name.**  
**The rank with the highest priority is deemed the “leader rank” (can be renamed) and only one person can have that rank. Whenever a new person joins the faction they will be assigned the rank with the lowest priority. Priorities are important because they determine who can do what. For example: you can’t kick someone with the same or higher rank than yourself. So if you have both Officers, and Co-leaders, do not fear officers kicking co-leaders or the co-leaders kicking each other. They can’t. The same goes for changing ranks, titles and other similar things.**  

**Now on to the commands:**  
/f rank manage ranks  
/f rank set <player><rank> set rank  
/f rank show <player> show rank  
/f rank list [page=1][faction=you] list ranks  
/f rank edit edit ranks  
/f rank edit create <name> <priority> [prefix=none] create rank  
/f rank edit delete <rank> [faction=you] delete rank  
/f rank edit name <rank> <new name> set rank name  
/f rank edit prefix <rank> <new prefix> set rank prefix  
/f rank edit priority <rank> <new priority> set rank priority  
**To figure out which ranks a faction has do /f rank list [page] [faction] which defaults to page 1 at your faction. To then set someones rank to one of the listed do /f rank set <player> <rank>. If you want to check someones rank do /f rank show <player>.**  
**Now that is all nice and sweet, but you want more control. You want more ranks. Then turn to /f rank edit. This command can only be used by the faction leader. Here you create a new rank by doing /f rank edit create <name> <priority> [prefix] both name and priority is mandatory and must be unique for that faction, the prefix is optional and does not have to be unique. You can edit either name, priority or prefix with the self-explanatory commands /f rank edit name <rank> <new name>, /f rank edit prefix <rank> <new prefix>and /f rank edit priority <rank> <new priority>. First type the rank name and the follow it by the new value of name, priority or prefix. Finally you can delete a rank if it is held by no-one that is done with /f rank delete <rank>.**  
###### Money
**The following commands are explained in this section:**  
/f money manage faction money  
/f money balance [faction=you] show faction money  
/f money deposit <amount> [faction=you] deposit to faction  
/f money withdraw <amount> [faction=you] withdraw from faction  
/f money ff <amount> <faction> <faction> transfer f –> f  
/f money fp <amount> <faction> <player> transfer f –> p  
/f money pf <amount> <player> <faction> transfer p –> f  
**If you have an economy plugin that supports Factions then all Factions can have money. To show the money a faction has do /f money balance [faction=you]. To put money into a faction account do /f money balance [faction=you] and to take them back do /f money withdraw <amount> [faction=you]. To transfer money from a faction to a player that is not you do /f money fp <amount> <faction> <player> and to transfer between two faction do /f money ff <amount> <faction> <faction>. If you are an admin you can also transfer money from another player to a specific faction with /f money pf <amount> <player> <faction>.**  
###### Territory
**The following commands are explained in this section:**  
/f seeChunk,sc [active=toggle] see the chunk you stand in  
/f territorytitles,tt [on|off=toggle] toggle territory titles  
/f claim claim faction territory  
/f claim one [faction=you] claim a single chunk  
/f claim auto [faction=you] claim as you walk around  
/f claim fill [faction=you] claim by filling  
/f claim square [radius=1] [faction=you] claim by square and radius  
/f claim circle [radius=1] [faction=you] claim by circle and radius  
/f claim all <all|map> <faction> claim all faction land  
/f unclaim unclaim faction territory  
/f unclaim one unclaim a single chunk  
/f unclaim auto unclaim as you walk around  
/f unclaim fill unclaim by filling  
/f unclaim square [radius=1] unclaim by square and radius  
/f unclaim circle[radius=1] unclaim by circle and radius  
/f unclaim all <all|map><faction>unclaim all faction land  
**Faction land is based on chunks. A chunk is a 16×16 block area and it can be claimed by one faction or by no factions at all. To see the borders of the chunk you are in type /f sc and to stop seeing it type /f sc again. Then you might want to claim some land for yourself. To claim just the chunk you stand in do /f claim one to claim everywhere you go do /f claim auto (and type that again to disable). If you have walked around in a circle while claiming and want to claim everything inside the circle (or square or pentagon or whatever) then do /f claim fill. If you would rather claim wheere you stand and all of your surroundings do /f claim square [radius] og /f claim circle [radius] to claim everything within a specified radius of chunks. You can only claim as many chunks as you have power, so if you want to claim something new you might have to unclaim something old. To do that simply /f unclaim and follow it up with any of the commands used of claiming.**  
###### Access
**In this section the following commands are covered:**
/f access manage access  
/f access view vies access  
/f access player <player> [yes/no=toggle] grant player access  
/f access faction <faction> [yes/no=toggle] grant player access  
**Sometimes you might want to give someone access to a specific chunk rather than all of you faction. That is the point of of access. With access you can give either a player or a faction the ability to build, open chests and interact in one specific chunk.
To see who has access in the chunk you are standing in type /f access view. To grant a player access in the chunk you are standing in type /f access player <playerName> yes and when you decide to take it away type /f access player <playerName> no. To grant a faction access in the chunk you are standing in type /f access faction <factionName> yes and when you decide to take it away type /f access faction <factionName> no.**
###### Relations
**This section covers the following commands:**  
/f relation manage faction relations  
/f relation set <faction> <relation> set relation wish to another faction  
/f relation list [page=1] [faction=you] [relations=all] list all factions with certain relation  
/f relation wishes [page=1] [faction=you] list the relation wishes  
**Two factions can have a relation between them. Per default the relation is neutral, but it can be changed to Enemy, Truce or Ally. The relation between the two factions is equal to the lowest wished relation between them. So if one wishes to be enemies and the other wishes to be truced, the enemy wish will prevail. If the Faction that wishes to be enemies then changes their wish to truce they will become truce because now both Factions wish to be truced.**  

| Wishes | Enemy | Neutral | Truce | Ally |
| --- | --- | --- | --- | --- |
|Enemy|Enemy|Enemy|Enemy|Enemy|
|Neutral|Enemy|Neutral|Neutral|Neutral|
|Truce|Enemy|Neutral|Truce|Truce|
|Ally|Enemy|Neutral|Truce|Ally|

**To set your wished to another faction type /f relation set <faction> <relation>. If you wished to be enemies you are now enemies, if you wish to be truced or allied the other faction must respond by setting the same relation wish.
To then see your relations type /f relation list and if you need to see the next page type /f relation list 2, to only see allies type /f relation list ally to see for another faction type /f relation list <factionName>. Now mix and match page, relation type and faction, to see the third page of enemies for the Faction Kalmar, type /f faction relation list 3 kalmar enemy.
If you would rather want to see relation wishes. That is not your current relations, but the relations you wish to have, type /f relation wishes.**
###### Permissions
**In this section the following commands are covered:**  
/f perm change faction permissions  
/f perm list [page=1] list perms  
/f perm show <perm>[faction=you ]show who has perm  
/f perm view <rank/rel/player/faction> [faction=you] view perms given to  
/f perm viewall <rank/rel/player/faction> [faction=you] view all perms held by  
/f perm set <perm> <rank/rel/player/faction> <yes/no> [faction=you] set perms  
**A faction has a list of permissions, that is who can do what. A permission can be given to either a rank, a. player, a relation, everyone in another faction or a specific rank in another faction.
To list all permissions type /f perm list. To show who has a specific perm type /f perm show <perm> per default permissions are only granted to ranks within your faction and a few perms are given to allies, but if you have changed it that will be displayed here.
If you want to know what permissions are specifically given to someone do /f perm view <someone>. If you want to check a rank, let’s say Officer, do /f perm view Officer to check allies do /f perm view ally, to check a player Madus you would do /f perm view Madus, to check a specific faction, let’s say Kalmar, do /f perm view Kalmar and to check permissions specifically given to officers of Kalmar do /f perm view Kalmar-Officer. This allows a high degree of granularity. Do you have a super-duper-best-friend ally, that is more important than your other allies you can give permissions to everyone in just that Faction, or even just people with a specific rank in a faction. Do you have a co-leader you can give permissions just to her (or you could create a co-leader rank) or you can give permissions to special people even when they are not a part of the faction.
If you want to check all permissions a player has you can do /f perm viewall <playerName>. This is all the permissions they have, not just the ones granted to them specifically. This is all permissions they have because of faction membership, rank, relation to your faction and the ones given to them specifically.
To set perms do /f perm set <perm> <someone> <yes/no>, you have to specify the perm (build, door, etc.) who has to get the perm and a yes/no to give it or take it away. The someone can be a rank, relation, individual player or a specific faction, just as explained earlier..**
###### Flags
**In this section the following commands are covered:**  
/f flag manage faction flags  
/f flag list [page=1] list flags  
/f flag show [faction=you] [page=1] show flags  
/f flag set <flag> <yes/no> [faction=you] set flags  
**Flags are on/off attributes of most factions. To list them do /f flag list, to show whether they are enabled or disabled for a specific faction do /f flag show <factionName> and to set them do /f flag set <flag> <yes/no>. Per default you can change whether your faction is open (which means everyone can join even without invitation), whether monsters can spawn in the territory and whether animals can spawn in the territory).**