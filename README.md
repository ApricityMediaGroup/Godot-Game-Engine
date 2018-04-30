[![Godot Engine logo](/logo.png)](https://godotengine.org)

## Godot Engine

Homepage: https://godotengine.org

#### 2D and 3D cross-platform game engine

Godot Engine is a feature-packed, cross-platform game engine to create 2D and
3D games from a unified interface. It provides a comprehensive set of common
tools, so that users can focus on making games without having to reinvent the
wheel. Games can be exported in one click to a number of platforms, including
the major desktop platforms (Linux, Mac OSX, Windows) as well as mobile
(Android, iOS) and web-based (HTML5) platforms.

### Documentation and demos

The official documentation is hosted on [ReadTheDocs](http://docs.godotengine.org).
It is maintained by the Godot community in its own [GitHub repository](https://github.com/godotengine/godot-docs).

The [class reference](http://docs.godotengine.org/en/latest/classes/)
is also accessible from within the engine.

The official demos are maintained in their own [GitHub repository](https://github.com/godotengine/godot-demo-projects)
as well.

There are also a number of other learning resources provided by the community,
such as text and video tutorials, demos, etc. Consult the [community channels](https://godotengine.org/community)
for more info.

[![Travis Build Status](https://travis-ci.org/godotengine/godot.svg?branch=master)](https://travis-ci.org/godotengine/godot)
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/bfiihqq6byxsjxxh/branch/master?svg=true)](https://ci.appveyor.com/project/akien-mga/godot)
[![Code Triagers Badge](https://www.codetriage.com/godotengine/godot/badges/users.svg)](https://www.codetriage.com/godotengine/godot)

### Apricity Custom
HOW TO: Compile Godot (Mono/C#) on Windows
*Make sure godot source is in c:/godot 
*NEED: VS 2017, Mono 5.2.0+, Python 3.5+., Pywin32, and SCons.
Find those here http://docs.godotengine.org/en/3.0/development/compiling/compiling_for_windows.html 
and here http://docs.godotengine.org/en/3.0/development/compiling/compiling_with_mono.html#doc-compiling-with-mono

1. Open VS2017 x64 Native Tools Command Prompt
2. cd to c:/godot 
3. Type 'scons -j6 p=windows vsproj=yes tools=yes module_mono_enabled=yes mono_glue=no' 
