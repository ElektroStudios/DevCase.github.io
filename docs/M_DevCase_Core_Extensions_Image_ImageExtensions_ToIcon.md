# ImageExtensions.ToIcon Method 
 

Converts an Image to a Icon.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Icon ToIcon(
	this Image sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToIcon ( 
	sender As Image
) As Icon
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim returnValue As Icon

returnValue = sender.ToIcon()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Icon^ ToIcon(
	Image^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToIcon : 
        sender : Image -> Icon 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd></dl>

#### Return Value
Type: Icon<br />The resulting Icon.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />