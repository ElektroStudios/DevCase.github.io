# SByteExtensions.ToIntPtr Method 
 

Converts a SByte value to an IntPtr.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_SByte">DevCase.Core.Extensions.SByte</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IntPtr ToIntPtr(
	this sbyte sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToIntPtr ( 
	sender As SByte
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim sender As SByte
Dim returnValue As IntPtr

returnValue = sender.ToIntPtr()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IntPtr ToIntPtr(
	signed char sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToIntPtr : 
        sender : sbyte -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.SByte<br />The source value.</dd></dl>

#### Return Value
Type: IntPtr<br />The resulting IntPtr.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type SByte. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim b As SByte = SByte.MaxValue
Dim value As IntPtr = b.ToIntPtr
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_SByte_SByteExtensions">SByteExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_SByte">DevCase.Core.Extensions.SByte Namespace</a><br />