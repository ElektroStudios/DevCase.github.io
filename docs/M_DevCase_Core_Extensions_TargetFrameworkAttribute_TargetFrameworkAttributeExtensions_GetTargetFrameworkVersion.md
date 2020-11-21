# TargetFrameworkAttributeExtensions.GetTargetFrameworkVersion Method 
 

Gets the .NET Framework version on which the source assembly was compiled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TargetFrameworkAttribute">DevCase.Core.Extensions.TargetFrameworkAttribute</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Version GetTargetFrameworkVersion(
	this TargetFrameworkAttribute sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetTargetFrameworkVersion ( 
	sender As TargetFrameworkAttribute
) As Version
```

**VB Usage**<br />
``` VB Usage
Dim sender As TargetFrameworkAttribute
Dim returnValue As Version

returnValue = sender.GetTargetFrameworkVersion()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Version^ GetTargetFrameworkVersion(
	TargetFrameworkAttribute^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetTargetFrameworkVersion : 
        sender : TargetFrameworkAttribute -> Version 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Runtime.Versioning.TargetFrameworkAttribute<br />The source TargetFrameworkAttribute.</dd></dl>

#### Return Value
Type: Version<br />The .NET Framework version on which the source assembly was compiled.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TargetFrameworkAttribute. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

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
<a href="T_DevCase_Core_Extensions_TargetFrameworkAttribute_TargetFrameworkAttributeExtensions">TargetFrameworkAttributeExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_TargetFrameworkAttribute">DevCase.Core.Extensions.TargetFrameworkAttribute Namespace</a><br />