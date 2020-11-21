# RectangleFExtensions.ScaleBySizeDifference Method 
 

Scale the size and position of the source RectangleF by the difference of the specified sizes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_RectangleF">DevCase.Core.Extensions.RectangleF</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static RectangleF ScaleBySizeDifference(
	this RectangleF sender,
	SizeF fromSize,
	SizeF toSize
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ScaleBySizeDifference ( 
	sender As RectangleF,
	fromSize As SizeF,
	toSize As SizeF
) As RectangleF
```

**VB Usage**<br />
``` VB Usage
Dim sender As RectangleF
Dim fromSize As SizeF
Dim toSize As SizeF
Dim returnValue As RectangleF

returnValue = sender.ScaleBySizeDifference(fromSize, 
	toSize)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static RectangleF ScaleBySizeDifference(
	RectangleF sender, 
	SizeF fromSize, 
	SizeF toSize
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ScaleBySizeDifference : 
        sender : RectangleF * 
        fromSize : SizeF * 
        toSize : SizeF -> RectangleF 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.RectangleF<br />The source RectangleF.</dd><dt>fromSize</dt><dd>Type: System.Drawing.SizeF<br />The source SizeF.</dd><dt>toSize</dt><dd>Type: System.Drawing.SizeF<br />The target SizeF.</dd></dl>

#### Return Value
Type: RectangleF<br />The resulting RectangleF.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RectangleF. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim oldSize As New SizeF(640, 480)
Dim oldRect As New RectangleF(New PointF(100, 100), New SizeF(639, 479))

Dim newSize As New SizeF(800, 600)
Dim newRect As RectangleF = ScaleBySizeDifference(oldRect, oldSize, newSize)

Console.WriteLine(String.Format("oldRect: {0}", oldRect.ToString())) ' {X=100,Y=100,Width=639,Height=479}
Console.WriteLine(String.Format("newRect: {0}", newRect.ToString())) ' {X=125,Y=125,Width=798.75,Height=598.75}
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_RectangleF_RectangleFExtensions">RectangleFExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_RectangleF">DevCase.Core.Extensions.RectangleF Namespace</a><br />