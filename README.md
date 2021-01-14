# PlayGroundApp

This is archive is a shipable running version (no Julia installation needed) of
https://github.com/oheil/PlayGround.jl

PlayGroundApp created using PackageCompiler:
```
julia> using PlayGround

(PlayGround) pkg> add PackageCompiler
   Updating registry at `C:\Users\oheil\.julia\registries\General`
   Updating git-repo `https://github.com/JuliaRegistries/General.git`
  Resolving package versions...
  Installed PackageCompiler ─ v1.2.5
Updating `C:\Users\oheil\.julia\dev\PlayGround\Project.toml`
  [9b87118b] + PackageCompiler v1.2.5
Updating `C:\Users\oheil\.julia\dev\PlayGround\Manifest.toml`
  [9b87118b] + PackageCompiler v1.2.5

julia> using PackageCompiler

julia> versioninfo()
Julia Version 1.5.3
Commit 788b2c77c1 (2020-11-09 13:37 UTC)
Platform Info:
  OS: Windows (x86_64-w64-mingw32)
  CPU: AMD Ryzen 9 3900X 12-Core Processor
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-9.0.1 (ORCJIT, znver2)
Environment:
  JULIA_EDITOR = "C:\Program Files\Microsoft VS Code\Code.exe"
  JULIA_NUM_THREADS = 1

julia> pwd() 
"C:\\Users\\oheil\\.julia\\dev\\PlayGround"

julia> create_app("..\\PlayGround", "PlayGroundApp")
┌ Warning: Revise has a dependency on Requires.jl, code in `@require` will not be run
└ @ PackageCompiler C:\Users\oheil\.julia\packages\PackageCompiler\3BsME\src\PackageCompiler.jl:544
┌ Warning: Package ModernGL has a build script, this might indicate that it is not relocatable
└ @ PackageCompiler C:\Users\oheil\.julia\packages\PackageCompiler\3BsME\src\PackageCompiler.jl:557
[ Info: PackageCompiler: creating base system image (incremental=false)...
[ Info: PackageCompiler: creating system image object file, this might take a while...
[ Info: PackageCompiler: creating system image object file, this might take a while...

```

