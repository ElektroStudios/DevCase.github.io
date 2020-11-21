# IconExtensions.ToImage Method 
 

Converts an Icon to an Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Icon">DevCase.Core.Extensions.Icon</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image ToImage(
	this Icon sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToImage ( 
	sender As Icon
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As Icon
Dim returnValue As Image

returnValue = sender.ToImage()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ ToImage(
	Icon^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToImage : 
        sender : Icon -> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Icon<br />The source Icon.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Icon. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Icon_IconExtensions">IconExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Icon">DevCase.Core.Extensions.Icon Namespace</a><br />