# BitmapSourceExtensions.ToImage Method (BitmapSource)
 

Converts the source BitmapSource to a Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_BitmapSource">DevCase.Core.Extensions.BitmapSource</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image ToImage(
	this BitmapSource sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToImage ( 
	sender As BitmapSource
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As BitmapSource
Dim returnValue As Image

returnValue = sender.ToImage()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ ToImage(
	BitmapSource^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToImage : 
        sender : BitmapSource -> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Media.Imaging.BitmapSource<br />The source BitmapSource.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type BitmapSource. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Remarks
Credits to author: https://stackoverflow.com/a/21931808/1248295

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_BitmapSource_BitmapSourceExtensions">BitmapSourceExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_BitmapSource_BitmapSourceExtensions_ToImage">ToImage Overload</a><br /><a href="N_DevCase_Core_Extensions_BitmapSource">DevCase.Core.Extensions.BitmapSource Namespace</a><br />