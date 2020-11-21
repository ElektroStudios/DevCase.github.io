# BitmapExtensions.ToIcon Method 
 

Converts a Bitmap to a Icon.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Icon ToIcon(
	this Bitmap sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToIcon ( 
	sender As Bitmap
) As Icon
```

**VB Usage**<br />
``` VB Usage
Dim sender As Bitmap
Dim returnValue As Icon

returnValue = sender.ToIcon()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Icon^ ToIcon(
	Bitmap^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToIcon : 
        sender : Bitmap -> Icon 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd></dl>

#### Return Value
Type: Icon<br />The resulting Icon.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />