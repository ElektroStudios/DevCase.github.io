# AssemblyExtensions.GetTargetFrameworkVersion Method 
 

Gets the target .NET Framework version on which the source assembly was compiled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Version GetTargetFrameworkVersion(
	this Assembly sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetTargetFrameworkVersion ( 
	sender As Assembly
) As Version
```

**VB Usage**<br />
``` VB Usage
Dim sender As [Assembly]
Dim returnValue As Version

returnValue = sender.GetTargetFrameworkVersion()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Version^ GetTargetFrameworkVersion(
	Assembly^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetTargetFrameworkVersion : 
        sender : Assembly -> Version 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Reflection.Assembly<br />The source Assembly.</dd></dl>

#### Return Value
Type: Version<br />The .NET Framework version on which the source assembly was compiled.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Assembly. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim asm As Assembly = Assembly.GetExecutingAssembly()
Dim targetFrameworkVersion As Version = GetTargetFrameworkVersion(asm)

Console.WriteLine(targetFrameworkVersion)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Assembly_AssemblyExtensions">AssemblyExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly Namespace</a><br />