# Discord API Methods

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/guilds/Server ID/bans/ 

Method : Get

Info : Returns all bans in json format including username, id, tag, and flags

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/guilds/Server ID/bans/User ID

Method : Delete

Info : Unbans the user based on the user ID

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/channels/Channel ID/messages

Method : Get

Info : Returns messages in json format includes id, type, content, attachements, embeds, mentions, pinned (bool), tts (bool), and timestamp

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/channels/Channel ID/messages

Method : Post

Info : Sends a message/embed if json data is {"content":"hi"}

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/auth/login

Method : Post

Info : Correct logins respond with authorization token

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/experiments

Method : Get

Info : Returns website fingerprint most info is currently unknown

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/auth/register

Method : Post

Info : Used to register a user with json data {"username":"username here"}

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/users/@me/billing/trials/USER ID/eligibility

Method : Get

Info : Returns the eligibility of billing

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/users/@me/affinities/guilds

Method : Get

Info : Returns all servers in json includes server ids and affinity

----------------------------------------------------------------------------------

URL : https://status.discord.com/api/v2/scheduled-maintenances/upcoming.json

Method : Get

Info : Returns current timezone of user and page id

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/applications/detectable
Method : Get
Info : Returns in json format the current buyable games/applications

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/users/@me/affinities/users

Method : Get

Info : Returns all friends user IDs

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/applications/public?application_ids=APP ID

Method : Get

Info : Returns friends current public game status if any

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/users/@me/relationships

Method : Get

Info : Returns all friends in list includes user id, usernames, avatar hashes, tag, and public flags

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/invites/INVITE URL?with_counts=true

Method : Get

Info : Returns invite code, server ID, server name, banner/splash hashes, icon hash, features, verification level, vanity url, and welcome screen if any

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/channels/CHANNEL ID/follower-stats

Method : Get

Info : Returns the current number of members that have seen the message, webhook source, and server ID

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/discoverable-guilds

Method : Get

Info : Responds with the current public servers including server name, id, banner hash, and invite

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/discovery/valid-term?term=TERM TO SEARCH

Method : Get

Info : Validates if search term is valid

----------------------------------------------------------------------------------

URL : https://discord.com/api/download?platform=PLATFORM

Method : Get

Info : Downloads the current version of the program

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/guilds

Method : Post

Info : Creates a server when json data includes {"name":"SERVER NAME"}

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/guilds/SERVER ID/premium/subscriptions

Method : Get

Info : Returns the current server boosters to a server includes server id 

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/guilds/SERVER ID/regions

Method : Patch

Info : Changes the server region 

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/guilds/SERVER ID

Method : Patch

Info : Send a post request including {"splash":"data:image//imagetype;BASE64 ENCODING OF IMAGE"} changes the background of server invite

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/guilds/SERVER ID/emojis

Method : Get

Info : Returns server emojis including ids, names, and time of added

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/channels/CHANNEL ID/webhooks

Method : Post

Info : Creates a webhook

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/guilds/SERVER ID/invites

Method : Get

Info : Returns invite codes

----------------------------------------------------------------------------------

URL : https://discord.com/api/v8/guilds/SERVER ID/integrations/ID

Method : Delete

Info : Deletes a integration

----------------------------------------------------------------------------------

URL : https://discordapp.com/__development/source_maps

Method : Get

Info : Returns the source map with in discord

----------------------------------------------------------------------------------

URL : https://discordapp.com/__development/create_build_override_link

Method : Patch

Info : Creates a build overide link 

----------------------------------------------------------------------------------

URL : https://discordapp.com/api/v8/sticker-packs

Method : Get

Info : Development will respond 403 without permision

----------------------------------------------------------------------------------

URL : https://discordapp.com/api/v8/users/@me/sticker-packs

Method : Get

Info : Trys to return a sticker pack not yet made 403 responce

----------------------------------------------------------------------------------

URL : http://127.0.0.1:3435/rpc?log

Method : Get

Info : Discord opens a port on your pc for rpc and its gay responds with a authorization token if logged into client or webapp

----------------------------------------------------------------------------------


