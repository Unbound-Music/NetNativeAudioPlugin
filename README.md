# NetNativeAudioPlugin (NNAP)
 NetNativeAudioPlugin (NNAP) is more that just another audio plugin library. NNAP is a complete development SDK allowing the creation of MANAGED .NET (C#) audio plugins that can target multiple plugins formats and operating systems from a SINGLE CODE BASE, natively, w/o the need for .NET when deployed.

## Feature Highlights

* Visual Studio Extension (2022)
* Visual Studio & .NET CLI templates for creating plugins. (net9)
* Integration with Avalonia UI (CLI, VS2022, JetBrains Rider) with support for XAML designers (VS2022, JetBrains Rider)
* Currently supported target plugin formats (VST3, CLAP\*)   
* Currently supported target operating systems (Windows, MacOS\*, Linux\*)
* Purely managed, fast interop, no C++/CLI.
* Compatible with NET9+ NativeAOT - Build native audio plugins with with zero dependencies!
* Provides builtin support for synchronizing automatically data models between Processors, Controllers, and UIs.
* Provided builtin support for automatic change notification and syncronization between data models and view models (MVVM)
- Supports multiple platforms: `win-x64`, `win-arm64`\*, `osx-x64`\*, `osx-arm64`\*, `linux-x64`\*, `linux-arm64`\*


\*Pre-Release Preview [Alpha] 

##
NNAP's foundation is rooted in the extensive [NPlug](https://github.com/xoofx/NPlug) .NET Native VST3 framework, [CppAst.NET](https://github.com/xoofx/CppAst.NET), and [CppAst.CodeGen](https://github.com/xoofx/CppAst.CodeGen) libraries created by [xoofx](https://github.com/xoofx) and expanded upon to support multiple plugin formats, user interfaces, and operating systems.  

##
VST is a registered trademark of Steinberg Media Technologies GmbH. 
>
Avalonia is a trademark of AvaloniaUI OÜ.
>
CLAP is open source plugin framework, released under the MIT license, that is the result of a multi-year project initiated by u-he and Bitwig, with design and implementation contributions by a group of commercial and open source audio developers from across our industry.
