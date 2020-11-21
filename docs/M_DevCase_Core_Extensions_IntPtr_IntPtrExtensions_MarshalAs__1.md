# IntPtrExtensions.MarshalAs(*T*) Method 
 

Marshals data from a unmanaged block of memory contained in the source IntPtr, to a new object of the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IntPtr">DevCase.Core.Extensions.IntPtr</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T MarshalAs<T>(
	this IntPtr sender
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function MarshalAs(Of T) ( 
	sender As IntPtr
) As T
```

**VB Usage**<br />
``` VB Usage
Dim sender As IntPtr
Dim returnValue As T

returnValue = sender.MarshalAs()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static T MarshalAs(
	IntPtr sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member MarshalAs : 
        sender : IntPtr -> 'T 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IntPtr<br />The source IntPtr.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The target Type to be marshaled from.</dd></dl>

#### Return Value
Type: *T*<br />The resulting object of the specified Type.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IntPtr. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IntPtr_IntPtrExtensions">IntPtrExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IntPtr">DevCase.Core.Extensions.IntPtr Namespace</a><br />