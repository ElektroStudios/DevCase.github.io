# UShortExtensions.ToUIntPtr Method 
 

Converts a UInt16 value to an UIntPtr.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_UShort">DevCase.Core.Extensions.UShort</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static UIntPtr ToUIntPtr(
	this ushort sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToUIntPtr ( 
	sender As UShort
) As UIntPtr
```

**VB Usage**<br />
``` VB Usage
Dim sender As UShort
Dim returnValue As UIntPtr

returnValue = sender.ToUIntPtr()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static UIntPtr ToUIntPtr(
	unsigned short sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToUIntPtr : 
        sender : uint16 -> UIntPtr 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.UInt16<br />The source value.</dd></dl>

#### Return Value
Type: UIntPtr<br />The resulting UIntPtr.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type UInt16. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As UIntPtr = 1US.ToUIntPtr()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_UShort_UShortExtensions">UShortExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_UShort">DevCase.Core.Extensions.UShort Namespace</a><br />