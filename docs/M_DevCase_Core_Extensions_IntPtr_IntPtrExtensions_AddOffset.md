# IntPtrExtensions.AddOffset Method 
 

Adds an offset to the value of the source IntPtr.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IntPtr">DevCase.Core.Extensions.IntPtr</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IntPtr AddOffset(
	this IntPtr ptr,
	long offset
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AddOffset ( 
	ptr As IntPtr,
	offset As Long
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim ptr As IntPtr
Dim offset As Long
Dim returnValue As IntPtr

returnValue = ptr.AddOffset(offset)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IntPtr AddOffset(
	IntPtr ptr, 
	long long offset
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AddOffset : 
        ptr : IntPtr * 
        offset : int64 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>ptr</dt><dd>Type: System.IntPtr<br />The source IntPtr.</dd><dt>offset</dt><dd>Type: System.Int64<br />The offset to add.</dd></dl>

#### Return Value
Type: IntPtr<br />A new IntPtr that reflects the addition of *offset* to *ptr*.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IntPtr. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IntPtr_IntPtrExtensions">IntPtrExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IntPtr">DevCase.Core.Extensions.IntPtr Namespace</a><br />