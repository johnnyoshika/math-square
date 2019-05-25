# math-square

My first NuGet package hosting on MyGet.

### What I did:
* Create a .Net Standard Class Library
* Add `MathUtil` class
* Toggle on `Project Properties` -> `Package` -> `Generate Nuget package on build`
* Push project to GitHub

### MyGet
* Create a feed: https://www.myget.org/BuildSource/List/johnny-test
* Under `Build Services`, add a build source from GitHub and link to this GitHub repo

### Client
* To consume this package, add this NuGet Package Source in Visual Studio: https://www.myget.org/F/johnny-test/api/v3/index.json
* Install `MathSquare` package

### Source/Symbols
* Allowed step-into source here: https://github.com/johnnyoshika/math-square/commit/c2cd9b605a1c697c69f032190b41530a90525caf
* Now in consuming client, disable `Just my code` in Visual Studio options:
  * `Debugging` -> `General` -> `Enable Just My Code`
* Update: this doesn't work (and it never did)! :-(

