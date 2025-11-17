# Haxe-Pong
Pong written in Haxe. Haxe pong. Pong.

A simple Pong game built with OpenFL that compiles to both HTML5 and Windows (C++). Features proper window resizing support and crisp text rendering across platforms.

# How to build

## Dependencies
Install dependencies with:
```bash
haxelib install haxelib.json
```

Then set up OpenFL and Lime (optional, but recommended):
```bash
haxelib run lime setup
haxelib run openfl setup
```

## Build commands
Test/debug:
```bash
openfl test <platform>
```

Release build:
```bash
openfl build <platform> -release -clean
```

**Supported platforms**: `html5` (JavaScript/web), `windows` (C++ executable)

