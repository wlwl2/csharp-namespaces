# csharp-namespaces

Namespaces and Assemblies in C#.

You should read https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/names-of-namespaces **first** for naming namespaces.

## Important

The following template specifies the general rule for naming namespaces:

`<Company>.(<Product>|<Technology>)[.<Feature>][.<Subnamespace>]`

The following are examples:

`Fabrikam.Math` `Litware.Security`

### Product/Technology Name

> DO use a stable, version-independent product name at the second level of a namespace name.

### Plural Namespace Names

> CONSIDER using plural namespace names where appropriate.

> For example, use System.Collections instead of System.Collection. Brand names and acronyms are exceptions to this rule, however. For example, use System.IO instead of System.IOs.

Source: https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/names-of-namespaces

> The assembly is the smallest versionable unit in the common language runtime.

> Assemblies take the form of executable (.exe) or dynamic link library (.dll) files, and are the building blocks of .NET applications.

Source: https://docs.microsoft.com/en-us/dotnet/standard/assembly/

### Core Namespaces

>Core namespaces include all System namespaces, excluding namespaces of the application models and the Infrastructure namespaces. Core namespaces include, among others, System, System.IO, System.Xml, and System.Net.

> DO NOT give types names that would conflict with any type in the Core namespaces.

Source: https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/names-of-namespaces

## Unity Documentation

https://docs.unity3d.com/Manual/cus-naming.html

https://docs.unity3d.com/Manual/upm-manifestPkg.html

https://docs.unity3d.com/Manual/Namespaces.html

https://docs.unity3d.com/Manual/upm-manifestPkg.html#displayName

https://docs.unity3d.com/Manual/ScriptCompilationAssemblyDefinitionFiles.html

## Microsoft Documentation

https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/namespaces/using-namespaces

https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/names-of-namespaces

https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/using-directive

https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/namespaces/

## Others

https://stackoverflow.com/questions/8934570/c-sharp-namespaces-and-assemblies-best-practice
