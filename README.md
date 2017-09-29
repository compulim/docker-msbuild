# MSBuild 2017 for Windows Container

Docker image with MSBuild 2017 for building .NET Framework, .NET Core, C#, F#, C++, and web projects. It is preinstalled with .NET Framework SDK 4.5 to 4.7, and Nuget 4.3.0.

List of preinstalled build tools can be found [here](https://docs.microsoft.com/en-us/visualstudio/install/workload-component-id-vs-build-tools).

Dockerfile can be found on [this](https://github.com/compulim/docker-msbuild/tree/master) GitHub repository.

# Usage

## MSBuild

MSBuild is located at `C:\Program Files (x86)\Microsoft Visual Studio\2017\BuildTools\MSBuild\15.0\Bin\MSBuild.exe`.

```
C:\Program Files (x86)\Microsoft Visual Studio\2017\BuildTools\MSBuild\15.0\Bin>MSBuild.exe /version
Microsoft (R) Build Engine version 15.3.409.57025 for .NET Framework
Copyright (C) Microsoft Corporation. All rights reserved.

15.3.409.57025
```

## Nuget

Nuget is located at `C:\Nuget\nuget.exe`.

```
C:\Nuget>nuget.exe
NuGet Version: 4.3.0.4406
usage: NuGet <command> [args] [options]
Type 'NuGet help <command>' for help on a specific command.
```

# Contribution

Like us? [Star](https://github.com/compulim/docker-msbuild/stargazers/) us.

Want to make it better? [Send](https://github.com/compulim/docker-msbuild/issues/) us your wish.
