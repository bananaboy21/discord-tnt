v1.5.0
Breaking changes!
Changes:
Added Custom collection which extends Map!
Add JSDoc comments! documentation is now out yay.
Improve webhookclient, added jsdoc and now using promises.
Resume handling.
Now its possible to check ping/websocket latency with Client#ping.
Handling websocket closing.
Two new events: Client#resume and Client#disconnect
Triggers when websocket resumes connection and disconnects.
Document and fix EmbedBuilder.
Get date of a snowflake ID by DiscordTNT#Snowflake!
RestMethods out, will be used with the library for simplier access to request methods, though its documented and you can use it as well if you know what your doing, Client#rest.
Self structure is out in beta, Client#self has some methods for managing the logged in bot such as changing presence or status etc, The game and status options from the client will be removed in the next updates.
Changes are untested and may not work.

v1.0.0
Fresh Release doesn't work as exected, versioning won't go up often till its stable.