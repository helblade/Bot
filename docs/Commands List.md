
### Administration  
Command and aliases | Description | Usage
----------------|--------------|-------
`.resetperms`  | Resets BOT's permissions module on this server to the default value. **Requires Administrator server permission.** | `.resetperms`
`.restart`  | Restarts the bot. Might not work. **Bot owner only.** | `.restart`
`.delmsgoncmd`  | Toggles the automatic deletion of user's successful command message to prevent chat flood. **Server Manager Only.** **Requires Administrator server permission.** | `.delmsgoncmd`
`.setrole` `.sr` | Sets a role for a given user.   **Requires ManageRoles server permission.** | `.sr @User Guest`
`.removerole` `.rr` | Removes a role from a given user.   **Requires ManageRoles server permission.** | `.rr @User Admin`
`.renamerole` `.renr` | Renames a role. Roles you are renaming must be lower than bot's highest role. **Requires ManageRoles server permission.** | `.renr "First role" SecondRole`
`.removeallroles` `.rar` | Removes all roles from a mentioned user.   **Requires ManageRoles server permission.** | `.rar @User`
`.createrole` `.cr` | Creates a role with a given name.   **Requires ManageRoles server permission.** | `.cr Awesome Role`
`.rolecolor` `.rc` | Set a role's color to the hex or 0-255 rgb color value provided.   **Requires ManageRoles server permission.** | `.rc Admin 255 200 100` or `.rc Admin ffba55`
`.ban` `.b` | Bans a user by ID or name with an optional message. **Requires BanMembers server permission.** | `.b "@some Guy" Your behaviour is toxic.`
`.softban` `.sb` | Bans and then unbans a user by ID or name with an optional message.   **Requires BanMembers server permission.** | `.sb "@some Guy" Your behaviour is toxic.`
`.kick` `.k` | Kicks a mentioned user.   **Requires KickMembers server permission.** | `.k "@some Guy" Your behaviour is toxic.`
`.mute`  | Mutes a mentioned user in a voice channel. **Requires MuteMembers server permission.** | `.mute @Someone`
`.unmute`  | Unmutes mentioned user or users.   **Requires MuteMembers server permission.** | `.unmute "@Someguy"` or `.unmute "@Someguy" "@Someguy"`
`.deafen` `.deaf` | Deafens mentioned user or users.   **Requires DeafenMembers server permission.** | `.deaf "@Someguy"` or `.deaf "@Someguy" "@Someguy"`
`.undeafen` `.undef` | Undeafens mentioned user or users.   **Requires DeafenMembers server permission.** | `.undef "@Someguy"` or `.undef "@Someguy" "@Someguy"`
`.delvoichanl` `.dvch` | Deletes a voice channel with a given name.   **Requires ManageChannels server permission.** | `.dvch VoiceChannelName`
`.creatvoichanl` `.cvch` | Creates a new voice channel with a given name.   **Requires ManageChannels server permission.** | `.cvch VoiceChannelName`
`.deltxtchanl` `.dtch` | Deletes a text channel with a given name.   **Requires ManageChannels server permission.** | `.dtch TextChannelName`
`.creatxtchanl` `.ctch` | Creates a new text channel with a given name.   **Requires ManageChannels server permission.** | `.ctch TextChannelName`
`.settopic` `.st` | Sets a topic on the current channel.   **Requires ManageChannels server permission.** | `.st My new topic`
`.setchanlname` `.schn` | Changes the name of the current channel.   **Requires ManageChannels server permission.** | `.schn NewName`
`.prune` `.clr` | `.prune` removes all nadeko's messages in the last 100 messages.`.prune X` removes last X messages from the channel (up to 100)`.prune @Someone` removes all Someone's messages in the last 100 messages.`.prune @Someone X` removes last X 'Someone's' messages in the channel.    | `.prune` or `.prune 5` or `.prune @Someone` or `.prune @Someone X`
`.die`  | Shuts the bot down. **Bot owner only.** | `@NadekoBot die`
`.setname` `.newnm` | Gives the bot a new name.   **Bot owner only.** | `.newnm BotName`
`.setavatar` `.setav` | Sets a new avatar image for the NadekoBot. Argument is a direct link to an image.   **Bot owner only.** | `.setav http://i.imgur.com/xTG3a1I.jpg`
`.setgame`  | Sets the bots game.   **Bot owner only.** | `.setgame Playing with kwoth`
`.send`  | Sends a message to someone on a different server through the bot.  Separate server and channel/user ids with `|` and prepend channel id with `c:` and user id with `u:`. **Bot owner only.** | `.send serverid|c:channelid` or `.send serverid|u:userid`
`.announce`  | Sends a message to all servers' general channel bot is connected to. **Bot owner only.** | `.announce Useless spam`
`.savechat`  | Saves a number of messages to a text file and sends it to you. **Bot owner only.** | `.savechat 150`
`.mentionrole` `.menro` | Mentions every person from the provided role or roles (separated by a ',') on this server. Requires you to have mention everyone permission. **Requires MentionEveryone server permission.** | `.menro RoleName`
`.donators`  | List of lovely people who donated to keep this project alive.  | `.donators`
`.donadd`  | Add a donator to the database. **Bot owner only.** | `.donadd Donate Amount`
`.antiraid_cmd`  | antiraid_desc **Requires Administrator server permission.** | antiraid_usage
`.antispam_cmd`  | antispam_desc **Requires Administrator server permission.** | antispam_usage
`.autoassignrole` `.aar` | Automaticaly assigns a specified role to every user who joins the server.  **Requires ManageRoles server permission.** | `.aar` to disable, `.aar Role Name` to enable
`.scsc`  | Starts an instance of cross server channel. You will get a token as a DM that other people will use to tune in to the same instance. **Bot owner only.** | `.scsc`
`.jcsc`  | Joins current channel to an instance of cross server channel using the token.  **Requires ManageServer server permission.** | `.jcsc TokenHere`
`.lcsc`  | Leaves Cross server channel instance from this channel.  **Requires ManageServer server permission.** | `.lcsc`
`.fwmsgs`  | Toggles forwarding of non-command messages sent to bot's DM to the bot owners **Bot owner only.** | `.fwmsgs`
`.fwtoall`  | Toggles whether messages will be forwarded to all bot owners or only to the first one specified in the credentials.json **Bot owner only.** | `.fwtoall`
`.logserver`  | Logs server activity in this channel. **Requires Administrator server permission.** **Bot owner only.** | `.logserver`
`.logignore`  | Toggles whether the .logserver command ignores this channel. Useful if you have hidden admin channel and public log channel. **Requires Administrator server permission.** **Bot owner only.** | `.logignore`
`.userpresence`  | Starts logging to this channel when someone from the server goes online/offline/idle.  **Requires Administrator server permission.** | `.userpresence`
`.voicepresence`  | Toggles logging to this channel whenever someone joins or leaves a voice channel you are in right now.  **Requires Administrator server permission.** | `.voicepresence`
`.repeatinvoke` `.repinv` | Immediately shows the repeat message and restarts the timer.   **Requires ManageMessages server permission.** | `.repinv`
`.repeat`  | Repeat a message every X minutes. If no parameters are specified, repeat is disabled.  | `.repeat 5 Hello there`
`.migratedata`  | Migrate data from old bot configuration **Bot owner only.** | `.migratedata`
`.rotateplaying` `.ropl` | Toggles rotation of playing status of the dynamic strings you specified earlier. **Bot owner only.** | `.ropl`
`.addplaying` `.adpl` | Adds a specified string to the list of playing strings to rotate. Supported placeholders: %servers%, %users%, %playing%, %queued% **Bot owner only.** | `.adpl`
`.listplaying` `.lipl` | Lists all playing statuses with their corresponding number. **Bot owner only.** | `.lipl`
`.removeplaying` `.rmpl` `.repl` | Removes a playing string on a given number.  **Bot owner only.** | `.rmpl`
`.slowmode`  | Toggles slow mode. When ON, users will be able to send only 1 message every 5 seconds.   **Requires ManageMessages server permission.** | `.slowmode`
`.asar`  | Adds a role to the list of self-assignable roles. **Requires ManageRoles server permission.** | `.asar Gamer`
`.rsar`  | Removes a specified role from the list of self-assignable roles. **Requires ManageRoles server permission.** | `.rsar`
`.lsar`  | Lists all self-assignable roles.  | `.lsar`
`.togglexclsar` `.tesar` | Toggles whether the self-assigned roles are exclusive. (So that any person can have only one of the self assignable roles) **Requires ManageRoles server permission.** | `.tesar`
`.iam`  | Adds a role to you that you choose. Role must be on a list of self-assignable roles.  | `.iam Gamer`
`.iamnot` `.iamn` | Removes a role to you that you choose. Role must be on a list of self-assignable roles.  | `.iamn Gamer`
`.leave`  | Makes Nadeko leave the server. Either name or id required.   **Bot owner only.** | `.leave 123123123331`
`.greetdel` `.grdel` | Toggles automatic deletion of greet messages.  **Requires ManageServer server permission.** | `.greetdel`
`.greet`  | Toggles anouncements on the current channel when someone joins the server.  **Requires ManageServer server permission.** | `.greet`
`.greetmsg`  | Sets a new join announcement message which will be shown in the server's channel. Type %user% if you want to mention the new member. Using it with no message will show the current greet message.  **Requires ManageServer server permission.** | `.greetmsg Welcome, %user%.`
`.greetdm`  | Toggles whether the greet messages will be sent in a DM (This is separate from greet - you can have both, any or neither enabled).  **Requires ManageServer server permission.** | `.greetdm`
`.greetdmmsg`  | Sets a new join announcement message which will be sent to the user who joined. Type %user% if you want to mention the new member. Using it with no message will show the current DM greet message.  **Requires ManageServer server permission.** | `.greetdmmsg Welcome to the server, %user%`.
`.bye`  | Toggles anouncements on the current channel when someone leaves the server. **Requires ManageServer server permission.** | `.bye`
`.byemsg`  | Sets a new leave announcement message. Type %user% if you want to mention the new member. Using it with no message will show the current bye message.  **Requires ManageServer server permission.** | `.byemsg %user% has left.`
`.byedel`  | Toggles automatic deletion of bye messages.  **Requires ManageServer server permission.** | `.byedel`
`.voice+text` `.v+t` | Creates a text channel for each voice channel only users in that voice channel can see.If you are server owner, keep in mind you will see them all the time regardless.   **Requires ManageRoles server permission.** **Requires ManageChannels server permission.** | `.voice+text`
`.cleanvplust` `.cv+t` | Deletes all text channels ending in `-voice` for which voicechannels are not found. **Use at your own risk. Needs Manage Roles and Manage Channels Permissions.** **Requires ManageChannels server permission.** **Requires ManageRoles server permission.** | `.cleanv+t`

### ClashOfClans  
Command and aliases | Description | Usage
----------------|--------------|-------
`,createwar` `,cw` | Creates a new war by specifying a size (>10 and multiple of 5) and enemy clan name.  | `,cw 15 The Enemy Clan`
`,startwar` `,sw` | Starts a war with a given number.  | `,sw 15`
`,listwar` `,lw` | Shows the active war claims by a number. Shows all wars in a short way if no number is specified.  | `,lw [war_number] or ,lw`
`,claim` `,call` `,c` | Claims a certain base from a certain war. You can supply a name in the third optional argument to claim in someone else's place.  | `,call [war_number] [base_number] [optional_other_name]`
`,claimfinish1` `,cf1` | Finish your claim with 1 star if you destroyed a base. First argument is the war number, optional second argument is a base number if you want to finish for someone else.  | `,cf1 1` or `,cf1 1 5`
`,claimfinish2` `,cf2` | Finish your claim with 2 stars if you destroyed a base. First argument is the war number, optional second argument is a base number if you want to finish for someone else.  | `,cf2 1` or `,cf2 1 5`
`,claimfinish` `,cf` | Finish your claim with 3 stars if you destroyed a base. First argument is the war number, optional second argument is a base number if you want to finish for someone else.  | `,cf 1` or `,cf 1 5`
`,endwar` `,ew` | Ends the war with a given index.  | `,ew [war_number]`
`,unclaim` `,ucall` `,uc` | Removes your claim from a certain war. Optional second argument denotes a person in whose place to unclaim  | `,uc [war_number] [optional_other_name]`

### CustomReactions  
Command and aliases | Description | Usage
----------------|--------------|-------
`.addcustreact` `.acr` | Add a custom reaction with a trigger and a response. Running this command in server requires Administration permission. Running this command in DM is Bot Owner only and adds a new global custom reaction. Guide here: <http://nadekobot.readthedocs.io/en/1.0/Custom%20Reactions/>  | `.acr "hello" Hi there %user%`
`.listcustreact` `.lcr` | Lists global or server custom reactions (15 commands per page). Running the command in DM will list global custom reactions, while running it in server will list that server's custom reactions.  | `.lcr 1`
`.showcustreact` `.scr` | Shows a custom reaction's response on a given ID.  | `.scr 1`
`.delcustreact` `.dcr` | Deletes a custom reaction on a specific index. If ran in DM, it is bot owner only and deletes a global custom reaction. If ran in a server, it requires Administration priviledges and removes server custom reaction.  | `.dcr 5`

### Gambling  
Command and aliases | Description | Usage
----------------|--------------|-------
`$raffle`  | Prints a name and ID of a random user from the online list from the (optional) role.  | `$raffle` or `$raffle RoleName`
`$cash` `$$$` | Check how much NadekoFlowers a person has. (Defaults to yourself)  | `$$$` or `$$$ @SomeGuy`
`$give`  | Give someone a certain amount of currency.  | `$give 1 "@SomeGuy"`
`$award`  | Awards someone a certain amount of currency.   **Bot owner only.** | `$award 100 @person`
`$take`  | Takes a certain amount of flowers from someone.   **Bot owner only.** | `$take 1 "@someguy"`
`$betroll` `$br` | Bets a certain amount of NadekoFlowers and rolls a dice. Rolling over 66 yields x2 flowers, over 90 - x3 and 100 x10.  | `$br 5`
`$leaderboard` `$lb` | Displays bot currency leaderboard.  | `$lb`
`$race`  | Starts a new animal race.  | `$race`
`$joinrace` `$jr` | Joins a new race. You can specify an amount of flowers for betting (optional). You will get YourBet*(participants-1) back if you win.  | `$jr` or `$jr 5`
`$roll`  | Rolls 0-100. If you supply a number [x] it rolls up to 30 normal dice. If you split 2 numbers with letter d (xdy) it will roll x dice from 1 to y.  | `$roll` or `$roll 7` or `$roll 3d5`
`$rolluo`  | Rolls X normal dice (up to 30) unordered. If you split 2 numbers with letter d (xdy) it will roll x dice from 1 to y.  | `$rolluo` or `$rolluo 7` or `$rolluo 3d5`
`$nroll`  | Rolls in a given range.  | `$nroll 5` (rolls 0-5) or `$nroll 5-15`
`$draw`  | Draws a card from the deck.If you supply number X, she draws up to 5 cards from the deck.  | `$draw` or `$draw 5`
`$shuffle` `$sh` | Reshuffles all cards back into the deck.  | `$sh`
`$flip`  | Flips coin(s) - heads or tails, and shows an image.  | `$flip` or `$flip 3`
`$betflip` `$bf` | Bet to guess will the result be heads or tails. Guessing awards you double flowers you've bet.  | `$bf 5 heads` or `$bf 3 t`

### Games  
Command and aliases | Description | Usage
----------------|--------------|-------
`>choose`  | Chooses a thing from a list of things  | `>choose Get up;Sleep;Sleep more`
`>8ball`  | Ask the 8ball a yes/no question.  | `>8ball should I do something`
`>rps`  | Play a game of rocket paperclip scissors with Nadeko.  | `>rps scissors`
`>linux`  | Prints a customizable Linux interjection  | `>linux Spyware Windows`
`>leet`  | Converts a text to leetspeak with 6 (1-6) severity levels  | `>leet 3 Hello`
`>poll`  | Creates a poll, only person who has manage server permission can do it.  | `>poll Question?;Answer1;Answ 2;A_3`
`>pollend`  | Stops active poll on this server and prints the results in this channel.  | `>pollend`
`>pick`  | Picks a flower planted in this channel.  | `>pick`
`>plant`  | Spend a flower to plant it in this channel. (If bot is restarted or crashes, flower will be lost)  | `>plant`
`>gencurrency` `>gc` | Toggles currency generation on this channel. Every posted message will have chance to spawn a NadekoFlower. Chance is specified by the Bot Owner. (default is 2%) **Requires ManageMessages server permission.** | `>gc`
`>typestart`  | Starts a typing contest.  | `>typestart`
`>typestop`  | Stops a typing contest on the current channel.  | `>typestop`
`>typeadd`  | Adds a new article to the typing contest. **Bot owner only.** | `>typeadd wordswords`
`>trivia` `>t` | Starts a game of trivia. You can add nohint to prevent hints.First player to get to 10 points wins by default. You can specify a different number. 30 seconds per question.  | `>t nohint` or `>t 5 nohint`
`>tl`  | Shows a current trivia leaderboard.  | `>tl`
`>tq`  | Quits current trivia after current question.  | `>tq`

### Help  
Command and aliases | Description | Usage
----------------|--------------|-------
`-modules` `-mdls` | Lists all bot modules.  | `-modules`
`-commands` `-cmds` | List all of the bot's commands from a certain module. You can either specify full, or only first few letters of the module name.  | `-commands Administration` or `-cmds Admin`
`-help` `-h` | Either shows a help for a single command, or DMs you help link if no arguments are specified.  | `-h !!q` or `-h`
`-hgit`  | Generates the commandlist.md file. **Bot owner only.** | `-hgit`
`-readme` `-guide` | Sends a readme and a guide links to the channel.  | `-readme` or `-guide`
`-donate`  | Instructions for helping the project financially.  | `-donate`

### Music  
Command and aliases | Description | Usage
----------------|--------------|-------
`!!next` `!!n` | Goes to the next song in the queue. You have to be in the same voice channel as the bot.  | `!!n`
`!!stop` `!!s` | Stops the music and clears the playlist. Stays in the channel.  | `!!s`
`!!destroy` `!!d` | Completely stops the music and unbinds the bot from the channel. (may cause weird behaviour)  | `!!d`
`!!pause` `!!p` | Pauses or Unpauses the song.  | `!!p`
`!!queue` `!!q` `!!yq` | Queue a song using keywords or a link. Bot will join your voice channel.**You must be in a voice channel**.  | `!!q Dream Of Venice`
`!!soundcloudqueue` `!!sq` | Queue a soundcloud song using keywords. Bot will join your voice channel.**You must be in a voice channel**.  | `!!sq Dream Of Venice`
`!!listqueue` `!!lq` | Lists 15 currently queued songs per page. Default page is 1.  | `!!lq` or `!!lq 2`
`!!nowplaying` `!!np` | Shows the song currently playing.  | `!!np`
`!!volume` `!!vol` | Sets the music volume 0-100%  | `!!vol 50`
`!!defvol` `!!dv` | Sets the default music volume when music playback is started (0-100). Persists through restarts.  | `!!dv 80`
`!!shuffle` `!!sh` | Shuffles the current playlist.  | `!!sh`
`!!playlist` `!!pl` | Queues up to 500 songs from a youtube playlist specified by a link, or keywords.  | `!!pl playlist link or name`
`!!soundcloudpl` `!!scpl` | Queue a soundcloud playlist using a link.  | `!!scpl soundcloudseturl`
`!!localplaylst` `!!lopl` | Queues all songs from a directory. **Bot owner only.** | `!!lopl C:/music/classical`
`!!radio` `!!ra` | Queues a radio stream from a link. It can be a direct mp3 radio stream, .m3u, .pls .asx or .xspf (Usage Video: <https://streamable.com/al54>)  | `!!ra radio link here`
`!!local` `!!lo` | Queues a local file by specifying a full path. **Bot owner only.** | `!!lo C:/music/mysong.mp3`
`!!move` `!!mv` | Moves the bot to your voice channel. (works only if music is already playing)  | `!!mv`
`!!remove` `!!rm` | Remove a song by its # in the queue, or 'all' to remove whole queue.  | `!!rm 5`
`!!movesong` `!!ms` | Moves a song from one position to another.  | `!! ms 5>3`
`!!setmaxqueue` `!!smq` | Sets a maximum queue size. Supply 0 or no argument to have no limit.  | `!!smq 50` or `!!smq`
`!!reptcursong` `!!rcs` | Toggles repeat of current song.  | `!!rcs`
`!!rpeatplaylst` `!!rpl` | Toggles repeat of all songs in the queue (every song that finishes is added to the end of the queue).  | `!!rpl`
`!!save`  | Saves a playlist under a certain name. Name must be no longer than 20 characters and mustn't contain dashes.  | `!!save classical1`
`!!load`  | Loads a playlist under a certain name.  | `!!load classical-1`
`!!playlists` `!!pls` | Lists all playlists. Paginated. 20 per page. Default page is 0.  | `!!pls 1`
`!!deleteplaylist` `!!delpls` | Deletes a saved playlist. Only if you made it or if you are the bot owner.  | `!!delpls animu-5`
`!!goto`  | Goes to a specific time in seconds in a song.  | `!!goto 30`
`!!getlink` `!!gl` | Shows a link to the song in the queue by index, or the currently playing song by default.  | `!!gl`
`!!autoplay` `!!ap` | Toggles autoplay - When the song is finished, automatically queue a related youtube song. (Works only for youtube songs and when queue is empty)  | `!!ap`

### NSFW  
Command and aliases | Description | Usage
----------------|--------------|-------
`~hentai`  | Shows a 2 random images (from gelbooru and danbooru) with a given tag. Tag is optional but preferred. Only 1 tag allowed.  | `~hentai yuri`
`~danbooru`  | Shows a random hentai image from danbooru with a given tag. Tag is optional but preffered. (multiple tags are appended with +)  | `~danbooru yuri+kissing`
`~gelbooru`  | Shows a random hentai image from gelbooru with a given tag. Tag is optional but preffered. (multiple tags are appended with +)  | `~gelbooru yuri+kissing`
`~rule34`  | Shows a random image from rule34.xx with a given tag. Tag is optional but preffered. (multiple tags are appended with +)  | `~rule34 yuri+kissing`
`~e621`  | Shows a random hentai image from e621.net with a given tag. Tag is optional but preffered. Use spaces for multiple tags.  | `~e621 yuri kissing`
`~cp`  | We all know where this will lead you to.  | `~cp`
`~boobs`  | Real adult content.  | `~boobs`
`~butts` `~ass` `~butt` | Real adult content.  | `~butts` or `~ass`

### Permissions  
Command and aliases | Description | Usage
----------------|--------------|-------
`;verbose` `;v` | Sets whether to show when a command/module is blocked.  | `;verbose true`
`;permrole` `;pr` | Sets a role which can change permissions. Or supply no parameters to find out the current one. Default one is 'Nadeko'.  | `;pr role`
`;listperms` `;lp` | Lists whole permission chain with their indexes. You can specify an optional page number if there are a lot of permissions.  | `;lp` or `;lp 3`
`;removeperm` `;rp` | Removes a permission from a given position  | `;rp 1`
`;moveperm` `;mp` | Moves permission from one position to another.  | `;mp 2 4`
`;srvrcmd` `;sc` | Sets a command's permission at the server level.  | `;sc "command name" disable`
`;srvrmdl` `;sm` | Sets a module's permission at the server level.  | `;sm "module name" enable`
`;usrcmd` `;uc` | Sets a command's permission at the user level.  | `;uc "command name" enable SomeUsername`
`;usrmdl` `;um` | Sets a module's permission at the user level.  | `;um "module name" enable SomeUsername`
`;rolecmd` `;rc` | Sets a command's permission at the role level.  | `;rc "command name" disable MyRole`
`;rolemdl` `;rm` | Sets a module's permission at the role level.  | `;rm "module name" enable MyRole`
`;chnlcmd` `;cc` | Sets a command's permission at the channel level.  | `;cc "command name" enable SomeChannel`
`;chnlmdl` `;cm` | Sets a module's permission at the channel level.  | `;cm "module name" enable SomeChannel`
`;allchnlmdls` `;acm` | Enable or disable all modules in a specified channel.  | `;acm enable #SomeChannel`
`;allrolemdls` `;arm` | Enable or disable all modules for a specific role.  | `;arm [enable/disable] MyRole`
`;allusrmdls` `;aum` | Enable or disable all modules for a specific user.  | `;aum enable @someone`
`;allsrvrmdls` `;asm` | Enable or disable all modules for your server.  | `;asm [enable/disable]`
`;ubl`  | Either [add]s or [rem]oves a user specified by a mention or ID from a blacklist. **Bot owner only.** | `;ubl add @SomeUser` or `;ubl rem 12312312313`
`;cbl`  | Either [add]s or [rem]oves a channel specified by an ID from a blacklist. **Bot owner only.** | `;cbl rem 12312312312`
`;sbl`  | Either [add]s or [rem]oves a server specified by a Name or ID from a blacklist. **Bot owner only.** | `;sbl add 12312321312` or `;sbl rem SomeTrashServer`
`;cmdcooldown` `;cmdcd` | Sets a cooldown per user for a command. Set to 0 to remove the cooldown.  | `;cmdcd "some cmd" 5`
`;allcmdcooldowns` `;acmdcds` | Shows a list of all commands and their respective cooldowns.  | `;acmdcds`
`;srvrfilterinv` `;sfi` | Toggles automatic deleting of invites posted in the server. Does not affect Bot Owner.  | `;sfi`
`;chnlfilterinv` `;cfi` | Toggles automatic deleting of invites posted in the channel. Does not negate the .srvrfilterinv enabled setting. Does not affect Bot Owner.  | `;cfi`
`;srvrfilterwords` `;sfw` | Toggles automatic deleting of messages containing forbidden words on the server. Does not affect Bot Owner.  | `;sfw`
`;chnlfilterwords` `;cfw` | Toggles automatic deleting of messages containing banned words on the channel. Does not negate the .srvrfilterwords enabled setting. Does not affect bot owner.  | `;cfw`
`;fw`  | Adds or removes (if it exists) a word from the list of filtered words. Use` ;sfw` or `;cfw` to toggle filtering.  | `;fw poop`
`;lstfilterwords` `;lfw` | Shows a list of filtered words.  | `;lfw`

### Searches  
Command and aliases | Description | Usage
----------------|--------------|-------
`~weather` `~we` | Shows weather data for a specified city and a country. BOTH ARE REQUIRED. Use country abbrevations.  | `~we Moscow RF`
`~youtube` `~yt` | Searches youtubes and shows the first result  | `~yt query`
`~imdb` `~omdb` | Queries omdb for movies or series, show first result.  | `~imdb Batman vs Superman`
`~randomcat` `~meow` | Shows a random cat image.  | `~meow`
`~randomdog` `~woof` | Shows a random dog image.  | `~woof`
`~img` `~i` | Pulls the first image found using a search parameter. Use ~ir for different results.  | `~i cute kitten`
`~ir`  | Pulls a random image using a search parameter.  | `~ir cute kitten`
`~lmgtfy`  | Google something for an idiot.  | `~lmgtfy query`
`~google` `~g` | Get a google search link for some terms.  | `~google query`
`~hearthstone` `~hs` | Searches for a Hearthstone card and shows its image. Takes a while to complete.  | `~hs Ysera`
`~urbandict` `~ud` | Searches Urban Dictionary for a word.  | `~ud Pineapple`
`~#`  | Searches Tagdef.com for a hashtag.  | `~# ff`
`~catfact`  | Shows a random catfact from <http://catfacts-api.appspot.com/api/facts>  | `~catfact`
`~revav`  | Returns a google reverse image search for someone's avatar.  | `~revav "@SomeGuy"`
`~revimg`  | Returns a google reverse image search for an image from a link.  | `~revimg Image link`
`~safebooru`  | Shows a random image from safebooru with a given tag. Tag is optional but preffered. (multiple tags are appended with +)  | `~safebooru yuri+kissing`
`~wikipedia` `~wiki` | Gives you back a wikipedia link  | `~wiki query`
`~color` `~clr` | Shows you what color corresponds to that hex.  | `~clr 00ff00`
`~videocall`  | Creates a private <http://www.appear.in> video call link for you and other mentioned people. The link is sent to mentioned people via a private message.  | `~videocall "@SomeGuy"`
`~av` `~avatar` | Shows a mentioned person's avatar.  | `~av "@SomeGuy"`
`~lolban`  | Shows top banned champions ordered by ban rate.  | `~lolban`
`~memelist`  | Pulls a list of memes you can use with `~memegen` from http://memegen.link/templates/  | `~memelist`
`~memegen`  | Generates a meme from memelist with top and bottom text.  | `~memegen biw "gets iced coffee" "in the winter"`
`~translate` `~trans` | Translates from>to text. From the given language to the destination language.  | `~trans en>fr Hello`
`~translangs`  | Lists the valid languages for translation.  | `~translangs`
`~anime` `~ani` `~aq` | Queries anilist for an anime and shows the first result.  | `~ani aquarion evol`
`~manga` `~mang` `~mq` | Queries anilist for a manga and shows the first result.  | `~mq Shingeki no kyojin`
`~yomama` `~ym` | Shows a random joke from <http://api.yomomma.info/>  | `~ym`
`~randjoke` `~rj` | Shows a random joke from <http://tambal.azurewebsites.net/joke/random>  | `~rj`
`~chucknorris` `~cn` | Shows a random chucknorris joke from <http://tambal.azurewebsites.net/joke/random>  | `~cn`
`~wowjoke`  | Get one of Kwoth's penultimate WoW jokes.  | `~wowjoke`
`~magicitem` `~mi` | Shows a random magicitem from <https://1d4chan.org/wiki/List_of_/tg/%27s_magic_items>  | `~mi`
`~osu`  | Shows osu stats for a player.  | `~osu Name` or `~osu Name taiko`
`~osub`  | Shows information about an osu beatmap.  | `~osub https://osu.ppy.sh/s/127712`
`~osu5`  | Displays a user's top 5 plays.  | `~osu5 Name`
`~pokemon` `~poke` | Searches for a pokemon.  | `~poke Sylveon`
`~pokemonability` `~pokeab` | Searches for a pokemon ability.  | `~pokeab overgrow`
`~hitbox` `~hb` | Notifies this channel when a certain user starts streaming. **Requires ManageMessages server permission.** | `~hitbox SomeStreamer`
`~twitch` `~tw` | Notifies this channel when a certain user starts streaming. **Requires ManageMessages server permission.** | `~twitch SomeStreamer`
`~beam` `~bm` | Notifies this channel when a certain user starts streaming. **Requires ManageMessages server permission.** | `~beam SomeStreamer`
`~liststreams` `~ls` | Lists all streams you are following on this server.  | `~ls`
`~removestream` `~rms` | Removes notifications of a certain streamer on this channel. **Requires ManageMessages server permission.** | `~rms SomeGuy`
`~checkstream` `~cs` | Checks if a user is online on a certain streaming platform.  | `~cs twitch MyFavStreamer`

### Utility  
Command and aliases | Description | Usage
----------------|--------------|-------
`.whosplaying` `.whpl` | Shows a list of users who are playing the specified game.  | `.whpl Overwatch`
`.inrole`  | Lists every person from the provided role or roles (separated by a ',') on this server. If the list is too long for 1 message, you must have Manage Messages permission.  | `.inrole Role`
`.checkmyperms`  | Checks your userspecific permissions on this channel.  | `.checkmyperms`
`.userid` `.uid` | Shows user ID.  | `.uid` or `.uid "@SomeGuy"`
`.channelid` `.cid` | Shows current channel ID.  | `.cid`
`.serverid` `.sid` | Shows current server ID.  | `.sid`
`.roles`  | List roles on this server or a roles of a specific user if specified. Paginated. 20 roles per page.  | `.roles 2` or `.roles @Someone`
`.channeltopic` `.ct` | Sends current channel's topic as a message.  | `.ct`
`.stats`  | Shows some basic stats for Nadeko.  | `.stats`
`.showemojis` `.se` | Shows a name and a link to every SPECIAL emoji in the message.  | `.se A message full of SPECIALemojis`
`.calculate` `.calc` | Evaluate a mathematical expression.  | `.calc 1+1`
`.calcops`  | Shows all available operations in .calc command  | `.calcops`
`.serverinfo` `.sinfo` | Shows info about the server the bot is on. If no channel is supplied, it defaults to current one.  | `.sinfo Some Server`
`.channelinfo` `.cinfo` | Shows info about the channel. If no channel is supplied, it defaults to current one.  | `.cinfo #some-channel`
`.userinfo` `.uinfo` | Shows info about the user. If no user is supplied, it defaults a user running the command.  | `.uinfo @SomeUser`
`...`  | Shows a random quote with a specified name.  | `... abc`
`..`  | Adds a new quote with the specified name and message.  | `.. sayhi Hi`
`.deletequote` `.delq` | Deletes a random quote with the specified keyword. You have to either be server Administrator or the creator of the quote to delete it.  | `.delq abc`
`.delallq` `.daq` | Deletes all quotes on a specified keyword. **Requires Administrator server permission.** | `.delallq kek`
`.remind`  | Sends a message to you or a channel after certain amount of time. First argument is me/here/'channelname'. Second argument is time in a descending order (mo>w>d>h>m) example: 1w5d3h10m. Third argument is a (multiword)message.  | `.remind me 1d5h Do something` or `.remind #general Start now!`
`.remindtemplate`  | Sets message for when the remind is triggered.  Available placeholders are %user% - user who ran the command, %message% - Message specified in the remind, %target% - target channel of the remind.   **Bot owner only.** | `.remindtemplate %user%, you gotta do %message%!`
`.convertlist`  | List of the convertible dimensions and currencies.  | `.convertlist`
`.convert`  | Convert quantities. Use `.convertlist` to see supported dimensions and currencies.  | `.convert m km 1000`