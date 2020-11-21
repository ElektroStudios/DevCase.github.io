# PointFExtensions.Flip Method 
 

Flips the X,Y coordinates of the specified PointF.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_PointF">DevCase.Core.Extensions.PointF</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static PointF Flip(
	this PointF sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Flip ( 
	sender As PointF
) As PointF
```

**VB Usage**<br />
``` VB Usage
Dim sender As PointF
Dim returnValue As PointF

returnValue = sender.Flip()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static PointF Flip(
	PointF sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Flip : 
        sender : PointF -> PointF 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.PointF<br />The source PointF to flip.</dd></dl>

#### Return Value
Type: PointF<br />The resulting PointF.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type PointF. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_PointF_PointFExtensions">PointFExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_PointF">DevCase.Core.Extensions.PointF Namespace</a><br />