# C# 平台以信息汇总

## `.NET Framework` 平台

`.NET Framework` 是旧的，面向Windows操作系统的平台，虽然他不再会获得功能性更新，但是微软仍然会每月一次的向`.NET Framework`提供安全性和可靠性补丁。  
所以对于已有的，基于`.NET Framework`的项目，没有必要因为安全担忧而迁移到`.NET`（旧称为 `.NET Core`），但是如果要进行新项目的开发，请使用`.NET 6`或更高版本（曾用名`.NET Core`）。  

关于`.NET Framework`的概述，可以查阅[这个页面](https://learn.microsoft.com/zh-cn/dotnet/framework/get-started/overview)。  
关于`.NET Framework`的操作系统支持信息，可以查阅[这个页面](https://learn.microsoft.com/zh-cn/dotnet/framework/get-started/system-requirements)。  

## `.NET` 平台（旧称为 `.NET Core`）

`.NET`（曾用名`.NET Core`）是新的，免费的跨平台开源平台，由 Microsoft 和开源社区维护。它定期更新，以确保用户将安全可靠的应用程序部署到生产中。  
相较于旧的`.NET Framework`，`.NET`拥有更好的性能，以及更多的功能和特性，如果没有[对`.NET Framework`中使用的陈旧技术的特别需求](https://learn.microsoft.com/zh-cn/dotnet/standard/choosing-core-framework-server#when-to-choose-net-framework)，则开发者永远应当使用`.NET`来作为开发首选。  

关于`.NET`的概述，可以查阅[这个页面](https://learn.microsoft.com/zh-cn/dotnet/core/introduction)。  
关于`.NET`的操作系统支持信息，可以查阅[这个页面中的markdown文件](https://github.com/search?q=repo%3Adotnet%2Fcore+path%3Asupported-os.md&type=code)。  
关于`.NET`的支持策略，可以查阅[这个页面](https://dotnet.microsoft.com/zh-cn/platform/support/policy)。  

## 平台一览

|平台<br>___________________________________|C#语言版本<br>_____________|.NET标准版本<br>____________|操作系统支持<br>_______________________|
|-|-|-|-|
|`.NET Framework 1.0`|`C# 1.0`|`netstandard1.1`|`Visual Studio .NET`|
|`.NET Framework 1.1` / `net11`|`C# 1.1`|`netstandard1.1`|`Windows Server 2003`|
|`.NET Framework 2.0` / `net20`|`C# 2`|`netstandard1.1`|`Windows Server 2003+`|
|`.NET Framework 3.0`|`C# 3`|`netstandard1.1`|`Windows Vista+`|
|`.NET Framework 3.5` / `net35`|`C# 3`|`netstandard1.1`|`Windows Vista+`|
|`.NET Framework 4.0` / `net40`|`C# 4`|`netstandard1.1`|`Windows Vista+`|
|`.NET Framework 4.5` / `net45`|`C# 5`|`netstandard1.1`|`Windows Vista+`|
|`.NET Framework 4.6` / `net46`|`C# 6`|`netstandard1.3`|`Windows Vista+`|
|`.NET Framework 4.6.1` / `net461`|`C# 7`|`netstandard2.0`|`Windows 7+`|
|`.NET Framework 4.6.2` / `net462`|`C# 7`|`netstandard2.0`|`Windows 7+`|
|`.NET Framework 4.7` / `net47`|`C# 7.1`|`netstandard2.0`|`Windows 7+`|
|`.NET Framework 4.7.1` / `net471`|`C# 7.2`|`netstandard2.0`|`Windows 7+`|
|`.NET Framework 4.7.2` / `net472`|`C# 7.3`|`netstandard2.0`|`Windows 7+`|
|`.NET Framework 4.8` / `net48`|`C# 8`|`netstandard2.0`|`Windows 7+`|
|`.NET Framework 4.8.1` / `net481`|`C# 8`|`netstandard2.0`|`Windows 10 20H2+`|
|`.NET Core 1.0` / `netcoreapp1.0`|`C# 6`|`netstandard1.6`|`Windows 7 SP1+` / `macOS 10.11+` / `Linux`|
|`.NET Core 2.0` / `netcoreapp2.0`|`C# 7`|`netstandard2.0`|`Windows 7 SP1+` / `macOS 10.12+` / `Linux`|
|`.NET Core 2.1` / `netcoreapp2.1`|`C# 7.3`|`netstandard2.0`|`Windows 7 SP1+` / `macOS 10.12+` / `Linux`|
|`.NET Core 2.2` / `netcoreapp2.2`|`C# 7.3`|`netstandard2.0`|`Windows 7 SP1+` / `macOS 10.12+` / `Linux`|
|`.NET Core 3.0` / `netcoreapp3.0`|`C# 8`|`netstandard2.1`|`Windows 7 SP1+` / `macOS 10.13+` / `Linux`|
|`.NET Core 3.1` / `netcoreapp3.1`|`C# 8`|`netstandard2.1`|`Windows 7 SP1+` / `macOS 10.15+` / `Linux`|
|`.NET (Core) 5` / `net5.0`|`C# 9`|`netstandard2.1`|`Windows 7 SP1+` / `macOS 10.15+` / `Linux`|
|`.NET (Core) 6` / `net6.0`|`C# 10`|`netstandard2.1`|`Windows 7 SP1+` / `macOS 10.15+` / `Linux` / `Android API 21+` / `iOS 10.0+`|
|`.NET (Core) 7` / `net7.0`|`C# 11`|`netstandard2.1`|`Windows 10 1607+` / `macOS 10.15+` / `Linux` / `Android API 21+` / `iOS 10.0+`|
|`.NET (Core) 8` / `net8.0`|`C# 12`|`netstandard2.1`|`Windows 10 1607+` / `macOS 12+` / `Linux` / `Android API 21+` / `iOS, iOS Simulator, tvOS, tvOS Simulator, MacCatalyst 12.0+`|
