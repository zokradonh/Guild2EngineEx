# Guild2EngineEx
Guild II has LUA modding capabilities. Unfortunately, it is very limited. Therefore, I decided to expand those by some GuildII.exe patches and this extension DLL.

Currently this extension adds the following LUA functions:

|Name|Description|
|---|---|
|GeeType(Number or Table or String or Boolean variable)|Returns the type of the variable as integer|
|GeeVersion()|Returns the current engine extension version (=2)|
|GeeLength(String or Table)|Returns the length of the parameter|


# How to Install
- Build solution of this project with Visual Studio 2017 or download the binary.
- Copy resulting `Guild2EngineEx.dll` to your Guild II program folder.
- Patch your GuildII.exe binary according to `gee.1337` in this repository with any hex editor. You can also use x96dbg to import the .1337 file and patch your executable.
