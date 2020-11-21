# SizeExtensions.ToSizeF Method 
 

Converts a Size to a SizeF.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Size">DevCase.Core.Extensions.Size</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static SizeF ToSizeF(
	this Size sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToSizeF ( 
	sender As Size
) As SizeF
```

**VB Usage**<br />
``` VB Usage
Dim sender As Size
Dim returnValue As SizeF

returnValue = sender.ToSizeF()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static SizeF ToSizeF(
	Size sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToSizeF : 
        sender : Size -> SizeF 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Size<br />The source Size.</dd></dl>

#### Return Value
Type: SizeF<br />The resulting SizeF.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Size. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Size_SizeExtensions">SizeExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Size">DevCase.Core.Extensions.Size Namespace</a><br />