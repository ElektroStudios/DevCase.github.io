# LongExtensions.ToIntPtr Method 
 

Converts a Int64 value to an IntPtr.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Long">DevCase.Core.Extensions.Long</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IntPtr ToIntPtr(
	this long sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToIntPtr ( 
	sender As Long
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim sender As Long
Dim returnValue As IntPtr

returnValue = sender.ToIntPtr()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IntPtr ToIntPtr(
	long long sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToIntPtr : 
        sender : int64 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Int64<br />The source value.</dd></dl>

#### Return Value
Type: IntPtr<br />The resulting IntPtr.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Int64. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As IntPtr = 1L.ToIntPtr()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Long_LongExtensions">LongExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Long">DevCase.Core.Extensions.Long Namespace</a><br />