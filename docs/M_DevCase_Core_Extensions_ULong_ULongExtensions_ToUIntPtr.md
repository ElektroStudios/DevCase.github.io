# ULongExtensions.ToUIntPtr Method 
 

Converts a UInt64 value to an UIntPtr.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ULong">DevCase.Core.Extensions.ULong</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static UIntPtr ToUIntPtr(
	this ulong sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToUIntPtr ( 
	sender As ULong
) As UIntPtr
```

**VB Usage**<br />
``` VB Usage
Dim sender As ULong
Dim returnValue As UIntPtr

returnValue = sender.ToUIntPtr()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static UIntPtr ToUIntPtr(
	unsigned long long sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToUIntPtr : 
        sender : uint64 -> UIntPtr 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.UInt64<br />The source value. 

 The value shouldn't exceed Int64.</dd></dl>

#### Return Value
Type: UIntPtr<br />The resulting UIntPtr.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type UInt64. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As UIntPtr = 1UL.ToUIntPtr()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ULong_ULongExtensions">ULongExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ULong">DevCase.Core.Extensions.ULong Namespace</a><br />