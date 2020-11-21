# RectangleExtensions.ScaleBySizeDifference Method 
 

Scale the size and position of the source Rectangle by the difference of the specified sizes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Rectangle">DevCase.Core.Extensions.Rectangle</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Rectangle ScaleBySizeDifference(
	this Rectangle sender,
	Size fromSize,
	Size toSize
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ScaleBySizeDifference ( 
	sender As Rectangle,
	fromSize As Size,
	toSize As Size
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim sender As Rectangle
Dim fromSize As Size
Dim toSize As Size
Dim returnValue As Rectangle

returnValue = sender.ScaleBySizeDifference(fromSize, 
	toSize)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Rectangle ScaleBySizeDifference(
	Rectangle sender, 
	Size fromSize, 
	Size toSize
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ScaleBySizeDifference : 
        sender : Rectangle * 
        fromSize : Size * 
        toSize : Size -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Rectangle<br />The source Rectangle.</dd><dt>fromSize</dt><dd>Type: System.Drawing.Size<br />The source Size.</dd><dt>toSize</dt><dd>Type: System.Drawing.Size<br />The target Size.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting Rectangle.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Rectangle. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim oldSize As New Size(640, 480)
Dim oldRect As New Rectangle(New Point(100, 100), New Size(639, 479))

Dim newSize As New Size(800, 600)
Dim newRect As Rectangle = ScaleBySizeDifference(oldRect, oldSize, newSize)

Console.WriteLine(String.Format("oldRect: {0}", oldRect.ToString())) ' {X=100,Y=100,Width=639,Height=479}
Console.WriteLine(String.Format("newRect: {0}", newRect.ToString())) ' {X=125,Y=125,Width=798,Height=598}
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Rectangle_RectangleExtensions">RectangleExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Rectangle">DevCase.Core.Extensions.Rectangle Namespace</a><br />