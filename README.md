# KlarWare-API
[client.EventCallback](#clienteventcallback)

[client.RunLua](#clientrunlua)

[cvar.FindCvar](#cvarfindcvar)

[convar.getint](#convargetint)

[convar.setint](#convarsetint)

[convar.getfloat](#convargetfloat)

[convar.setfloat](#convarsetfloat)

[convar.setchar](#convarsetchar)

client.EventCallback
--------------------------------
  ```lua
  -- callback name, function
client.EventCallback("on_paint", function ()
  -- code
  end)
 
  ```
--------------------------------
client.RunLua
--------------------------------
  ```lua
  -- lua name
client.RunLua("test.lua")
  ```
--------------------------------
cvar.FindCvar
--------------------------------
  ```lua
  -- cvar name
client.FindCvar("bot_stop")
  ```
--------------------------------
convar.getint
--------------------------------
  ```lua
  -- convar name
convar.getint("bot_stop")
  -- example:
  test = convar.getint("bot_stop")
  print(test)
  ```
--------------------------------
convar.setint
--------------------------------
  ```lua
  -- convar name, value
convar.setint("bot_stop", 1)
  -- example:
	bot_stop = cvar.FindCvar("bot_stop")
	convar.setint(bot_stop, 1)
  ```
--------------------------------
convar.getfloat
--------------------------------
  ```lua
  -- convar name
convar.getfloat("snd_mvp_volume")
  -- example:
  test = convar.getfloat("snd_mvp_volume")
  print(test)
  ```
--------------------------------
convar.setfloat
--------------------------------
  ```lua
  -- convar name,  value
convar.setfloat("snd_mvp_volume", 0.3)
  -- example:
	snd_mvp_volume = cvar.FindCvar("snd_mvp_volume")
	convar.setfloat(bot_stop, 0.3)
  ```
--------------------------------
convar.setchar
--------------------------------
  ```lua
  -- convar name, name
convar.setchar("jpeg", "mirage.jpg")
  ```
--------------------------------
