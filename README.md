# SJ In-Game Console
This is a libGDX library that allows a developer to add a console (similar to how it is featured in Source games) to
their game. This repo is an update to [an earlier repo](https://github.com/StrongJoshua/libgdx-inGameConsole) by
StrongJoshua, and has the same usage but also includes some bug fixes/build fixes. Check out the changelog at
[StrongJoshua's website](https://www.strongjoshua.net/projects/games/libgdx-ingame-console)!

### How it works
Essentially what the console allows you to do is specify commands that you will be able to access from within the game,
using the console. The console also enables live logging from within the application.

### Purpose
This console speeds up development substantially by removing the need to recompile a program every time a minute change
is made, specifically in regard to manipulating constants or other values when balancing a game, for example.

### Integration
#### Gradle
Add the following line to your build.gradle file under the dependencies section of the **core** project:  

`api "com.github.tommyettinger:sjInGameConsole:$inGameConsoleVersion"`  

Replace **$inGameConsoleVersion** with the newest version number! You can also use a commit hash from JitPack as a
version number.

If you have a GWT project, add this line to the dependencies section of the **html** project, also replacing
**$inGameConsoleVersion** as before:

`implementation "com.github.tommyettinger:sjInGameConsole:$inGameConsoleVersion:sources"`

Then simply right-click the project and choose `Gradle->Refresh All`.

Versions
========
Latest Stable: **1.0.0** (see [previous repo](https://github.com/StrongJoshua/libgdx-inGameConsole))
Latest Snapshot: **1.0.1-SNAPSHOT**

License
=======
Copyright 2024

Licensed under the Apache License, Version 2.0 (the "License");
you may not use these files except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
