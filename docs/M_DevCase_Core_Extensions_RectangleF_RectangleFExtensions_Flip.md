# RectangleFExtensions.Flip Method 
 

Flips the location and size of the specified RectangleF.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_RectangleF">DevCase.Core.Extensions.RectangleF</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static RectangleF Flip(
	this RectangleF sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Flip ( 
	sender As RectangleF
) As RectangleF
```

**VB Usage**<br />
``` VB Usage
Dim sender As RectangleF
Dim returnValue As RectangleF

returnValue = sender.Flip()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static RectangleF Flip(
	RectangleF sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Flip : 
        sender : RectangleF -> RectangleF 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.RectangleF<br />The source RectangleF to flip.</dd></dl>

#### Return Value
Type: RectangleF<br />The resulting RectangleF.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RectangleF. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_RectangleF_RectangleFExtensions">RectangleFExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_RectangleF">DevCase.Core.Extensions.RectangleF Namespace</a><br />