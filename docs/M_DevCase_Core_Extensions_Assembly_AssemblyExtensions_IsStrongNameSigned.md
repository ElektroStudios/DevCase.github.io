# AssemblyExtensions.IsStrongNameSigned Method 
 

Gets a value that determine whether the source Assembly is strong-name signed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsStrongNameSigned(
	this Assembly sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsStrongNameSigned ( 
	sender As Assembly
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As [Assembly]
Dim returnValue As Boolean

returnValue = sender.IsStrongNameSigned()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsStrongNameSigned(
	Assembly^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsStrongNameSigned : 
        sender : Assembly -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Reflection.Assembly<br />The source Assembly.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the source Assembly is strong-name signed; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Assembly. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim asm As Assembly = Assembly.GetExecutingAssembly()
Dim isStrongNameSigned As Boolean = IsStrongNameSigned(asm)

Console.WriteLine(isStrongNameSigned.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Assembly_AssemblyExtensions">AssemblyExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly Namespace</a><br />