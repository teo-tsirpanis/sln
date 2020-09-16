[![Nuget](https://img.shields.io/nuget/v/Sln)](https://nuget.org/packages/Sln)

__Note:__ Unless you want to support reading files inside solution folders, use [the official `Microsoft.Build` package](https://nuget.org/packages/Microsoft.Build) instead.

See more at https://github.com/Microsoft/msbuild/issues/1708#issuecomment-280693611

Reuse some source files from https://github.com/Microsoft/msbuild/ repo
and reimplement some classes to not import too many files.

Since version 0.4.0, the library's namespace is `EnricoSada.MSBuild` to allow using it side-by-side with `Microsoft.Build`.
