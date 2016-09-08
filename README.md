# lua5-vsproject
Visual Studio project files for compiling Lua 5.3

## Supported Visual Studio versions
- VS2013
- VS2015

## Usage
Put this repository into the Lua source code directory,
and open the desired version of `Lua5.sln` in Visual Studio, e.g.,
```
lua-5.3.3
+--doc
+--src
+--lua5-vsproject
   +--vs2013
      +--Lua5.sln
   +--vs2015
      +--Lua5.sln
```

## Output files
- Static libary: `liblua.lib` (x86 and x64)
- Compiler: `luac.exe` (x86 and x64)
- Interpreter: `lua.exe` (x86 and x64)
