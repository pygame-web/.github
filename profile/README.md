# Welcome everyone, 

### Here you will get to run your python/pygame code directly inside web browsers.

[Visit pygame-web.github.io page](https://pygame-web.github.io) (this is the documentation for pygbag the ready made tool you want to try first)


Porting binary module (eg c/c++) is possible too, but is not documented at the moment and requires github CI (or a Linux based operating system)
see https://github.com/pygame-web/pkg-porting-wasm/issues for more.

____

Pygbag C runtime uses libpython WebAssembly from:

[CPython Wasm builds](https://github.com/python/cpython/tree/main/Tools/wasm)

and contains code adapted from :


[Panda3D](https://github.com/panda3d/panda3d) and [WebGLport support modules](https://github.com/rdb/cpython-emscripten-modules) [doc](https://rdb.name/panda3d-webgl.md#supplementalmodules)

Please note that though pygame-web hosts a Panda3D wasm wheel it is not production ready (but worth trying !).

____

But really, how does it work ?

Witchcraft of course ! 

But better [read the Real Answer](https://stackoverflow.com/questions/76265735/does-pygbag-directly-interprets-python-in-the-browser-or-compiles-it-to-wasm-and/77115432#77115432)



____

Special Thanks apply to our sponsors :

[https://www.browserstack.com](https://www.browserstack.com/open-source) : for ability to test iOS/Safari



### pygbag network api

Please note that thanks to some recent money donations we will be able to provide a hub+api for multiplayer games for at least one year.
Of course donors are granted as much applications ID they need as long the service costs can be splitted amongst them.

For others please apply on pygame-web channel of Pygame Community Discord for temporary free access (all developpers IP addresses will be required in case of teams).

No adult content whatsoever will be tolerated and lobbies/chats/ingame will be monitored for abuse or ill behaviour on the standard network (websockets). Please adopt self moderation behaviour.

WebRTC should not be monitored, you are welcome to implement your bootstrap as long as you do not advertise for it and do not ask for it. Be smart and use friend-to-friend topology.

