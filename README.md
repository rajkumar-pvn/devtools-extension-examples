Firefox DevTools Extension Examples
===================================

This repository contains extensions for Firefox native developer tools
showing how to build extensions and use existing platform API.

CustomTheme
-----------
This extension shows how to implement new theme for developer tools Toolbox.

Related API:
    gDevTools.registerTheme()
    gDevTools.unregisterTheme()

CustomActor
-----------
This extension shows how to implement tools/features that can be used
to debug/inspect remote devices. Learn how to properly implement both:
the client and sever side of new tool.

    Actor
    ActorFront
    registerActor()
