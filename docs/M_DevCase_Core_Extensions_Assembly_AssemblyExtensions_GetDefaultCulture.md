# AssemblyExtensions.GetDefaultCulture Method 
 

Gets the default CultureInfo (if any) of the source Assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static CultureInfo GetDefaultCulture(
	this Assembly sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetDefaultCulture ( 
	sender As Assembly
) As CultureInfo
```

**VB Usage**<br />
``` VB Usage
Dim sender As [Assembly]
Dim returnValue As CultureInfo

returnValue = sender.GetDefaultCulture()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static CultureInfo^ GetDefaultCulture(
	Assembly^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetDefaultCulture : 
        sender : Assembly -> CultureInfo 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Reflection.Assembly<br />The source Assembly.</dd></dl>

#### Return Value
Type: CultureInfo<br />The default CultureInfo of the source Assembly.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Assembly. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim asm As Assembly = Assembly.GetExecutingAssembly()
Dim ci As CultureInfo = GetDefaultCulture(asm)

Console.WriteLine(ci.Name)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Assembly_AssemblyExtensions">AssemblyExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly Namespace</a><br />