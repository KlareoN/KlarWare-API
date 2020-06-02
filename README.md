# KlarWare-API
[client.EventCallback](#clienteventcallback)

[client.RunLua](#clientrunlua)
----------------------------------------------------------------
[cvar.AllocateDLLIdentifier](#cvarallocatedllIdentifier)

[cvar.RegisterConCommand](#cvarregisterconcommand)

[cvar.UnregisterConCommand](#cvarunregisterconcommand)

[cvar.UnregisterConCommands](#cvarunregisterconcommands)

[cvar.GetCommandLineValue](#cvargetcommandlinevalue)

[cvar.FindCommandBase](#cvarfindcommandbase)

[cvar.FindVar](#cvarfindvar)

[cvar.FindCommand](#cvarfindcommand)

[cvar.InstallGlobalChangeCallback](#cvarinstallglobalchangecallback)

[cvar.RemoveGlobalChangeCallback](#cvarremoveglobalchangecallback)

[cvar.CallGlobalChangeCallbacks](#cvarcallglobalchangecallbacks)

[cvar.InstallConsoleDisplayFunc](#cvarinstallconsoledisplayfunc)

[cvar.RemoveConsoleDisplayFunc](#cvarremoveconsoledisplayfunc)

[cvar.ConsoleColorPrintf](#cvarconsolecolorprintf)

[cvar.ConsolePrintf](#cvarconsoleprintf)

[cvar.ConsoleDPrintf](#cvarconsoledprintf)

[cvar.RevertFlaggedConVars](#cvarrevertflaggedconvars)
----------------------------------------------------------------

[convar.SetInt](#convarsetint)

[convar.SetFloat](#convarsetfloat)

[convar.GetInt](#convargetint)

[convar.GetFloat](#convargetfloat)

----------------------------------------------------------------

client.EventCallback
--------------------------------
  ```lua
  -- callback name, function
client.EventCallback("PaintTraverse", function ()
  -- code
  end)
  -- callback name
  PaintTraverse()
  CreateMove(cmd)
  OverrideView(vsView)
  FrameStageNotify(stage)
  ```
--------------------------------
client.RunLua
--------------------------------
  ```lua
  -- lua name
client.RunLua("test.lua")
  ```
--------------------------------
cvar.AllocateDLLIdentifier
--------------------------------
  ```lua
cvar.AllocateDLLIdentifier()
  ```
--------------------------------
cvar.RegisterConCommand
--------------------------------
  ```lua
  -- command name
cvar.RegisterConCommand(command)

  ```
--------------------------------
cvar.UnregisterConCommand
--------------------------------
  ```lua
  -- command name
cvar.UnregisterConCommand(command)

  ```
--------------------------------
cvar.UnregisterConCommands
--------------------------------
  ```lua
cvar.UnregisterConCommands(id)

  ```
--------------------------------
cvar.GetCommandLineValue
--------------------------------
  ```lua
  -- VariableName name
cvar.GetCommandLineValue(VariableName)

  ```
--------------------------------
cvar.FindCommandBase
--------------------------------
  ```lua
  -- name
cvar.FindCommandBase(name)

  ```
--------------------------------
cvar.FindVar
--------------------------------
  ```lua
  -- var_name name
cvar.FindVar(var_name)

  ```
--------------------------------
cvar.FindCommand
--------------------------------
  ```lua
  -- name
cvar.FindCommand(name)

  ```
--------------------------------
cvar.InstallGlobalChangeCallback
--------------------------------
  ```lua
  -- callback name
cvar.InstallGlobalChangeCallback(callback)

  ```
--------------------------------
cvar.RemoveGlobalChangeCallback
--------------------------------
  ```lua
  -- callback name
cvar.RemoveGlobalChangeCallback(callback)

  ```
--------------------------------
cvar.CallGlobalChangeCallbacks
--------------------------------
  ```lua
  -- var, pOldString, flOldValue
cvar.CallGlobalChangeCallbacks(var, pOldString, flOldValue)

  ```
--------------------------------
cvar.InstallConsoleDisplayFunc
--------------------------------
  ```lua
  -- DisplayFunc
cvar.InstallConsoleDisplayFunc(DisplayFunc)

  ```

--------------------------------
cvar.RemoveConsoleDisplayFunc
--------------------------------
  ```lua
  -- DisplayFunc
cvar.RemoveConsoleDisplayFunc(DisplayFunce)

  ```

--------------------------------
cvar.ConsoleColorPrintf
--------------------------------
  ```lua
  -- Color(255,255,255), name
cvar.ConsoleColorPrintf(Color, name)

  ```

--------------------------------
cvar.ConsolePrintf
--------------------------------
  ```lua
  -- name
cvar.ConsolePrintf(name)

  ```

--------------------------------
cvar.ConsoleDPrintf
--------------------------------
  ```lua
  -- name
cvar.ConsoleDPrintf(name)

  ```

--------------------------------
cvar.RevertFlaggedConVars
--------------------------------
  ```lua
  -- nFlag
cvar.RevertFlaggedConVars(nFlag)

  ```

--------------------------------
convar.SetInt
--------------------------------
  ```lua
  -- name, int
convar.SetInt(name, int)

  ```

--------------------------------
convar.SetFloat
--------------------------------
  ```lua
  -- name, float
convar.SetFloat(name, float)

  ```

--------------------------------
convar.GetInt
--------------------------------
  ```lua
  -- name
convar.GetInt(name)

  ```

--------------------------------
convar.GetFloat
--------------------------------
  ```lua
  -- name
convar.GetFloat(name)

  ```
