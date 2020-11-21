# RectangleFExtensions.ScaleByFactor Method 
 

Scale the size and position of the source RectangleF by the specified percentage factor.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_RectangleF">DevCase.Core.Extensions.RectangleF</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static RectangleF ScaleByFactor(
	this RectangleF sender,
	float factor
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ScaleByFactor ( 
	sender As RectangleF,
	factor As Single
) As RectangleF
```

**VB Usage**<br />
``` VB Usage
Dim sender As RectangleF
Dim factor As Single
Dim returnValue As RectangleF

returnValue = sender.ScaleByFactor(factor)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static RectangleF ScaleByFactor(
	RectangleF sender, 
	float factor
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ScaleByFactor : 
        sender : RectangleF * 
        factor : float32 -> RectangleF 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.RectangleF<br />The source RectangleF.</dd><dt>factor</dt><dd>Type: System.Single<br />The percentage factor.</dd></dl>

#### Return Value
Type: RectangleF<br />The resulting RectangleF.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RectangleF. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim oldRect As New RectangleF(New PointF(100, 100), New SizeF(100, 100))
Dim newRect As RectangleF = ScaleByFactor(oldRect, 2.0F)

Console.WriteLine(String.Format("oldRect: {0}", oldRect.ToString())) ' {X=100,Y=100,Width=100,Height=100}
Console.WriteLine(String.Format("newRect: {0}", newRect.ToString())) ' {X=200,Y=200,Width=200,Height=200}
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_RectangleF_RectangleFExtensions">RectangleFExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_RectangleF">DevCase.Core.Extensions.RectangleF Namespace</a><br />