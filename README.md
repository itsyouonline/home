## Home of the ItsYou.online product organization

This repository is the starting point for people to find their way in all other repos in the Itsyou.online product organization.

- owner of this organization = Rob Van Mieghem  
  backup = Lee Smet

- [Kanban](https://waffle.io/itsyouonline/home)


Milestones:
- [0.9.14 and older](https://waffle.io/itsyouonline/home?milestone=0.9.10,0.9.11,0.9.12,0.9.14)
  * Russian translations
  * Minor improvements and bugfixes
  * Ready for telegram integration
  * before end of july
- [1.0](https://waffle.io/itsyouonline/home?milestone=1.0)
  * end of summer
  * Ability for users to share information directly
  * Public profiles and information sharing
  * Contract management through the UI

Code Repos:
- [Identityserver](https://github.com/itsyouonline/identityserver)
- [Telegram Integration](https://github.com/itsyouonline/identityserver)
- [loginsrv](https://github.com/itsyouonline/loginsrv) a fork of [caddy loginsrv](https://github.com/tarent/loginsrv) to enable the plugin to oauth against itsyou.online
- [filemanager](https://github.com/itsyouonline/filemanager) a fork of [caddy filemanager](https://github.com/hacdias/loginsrv) to enable the plugin to oauth against itsyou.online
- [Caddy Integration](https://github.com/itsyouonline/caddy-integration) contains [oauth](https://github.com/itsyouonline/caddy-integration/tree/master/oauth) plugin which enables caddy to authorize users against itsyou.online. Also contains examples for using other plugins ([loginsrv examples](https://github.com/itsyouonline/caddy-integration/tree/master/examples/loginsrv), [filemanager examples](https://github.com/itsyouonline/caddy-integration/tree/master/examples/filemanager)) with itsyou.online 
- [examples_nodejs](https://github.com/itsyouonline/examples_nodejs) contains a complete example for using node.js with expreass and passport.js modules to oauth against itsyou.online
