# TemplateMatchExtensions.ToScreenCoordinates Method 
 

Translates the size and location of the source TemplateMatch to screen coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_AForge_Extensions_TemplateMatch">DevCase.ThirdParty.AForge.Extensions.TemplateMatch</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Rectangle ToScreenCoordinates(
	this TemplateMatch match,
	IntPtr window
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToScreenCoordinates ( 
	match As TemplateMatch,
	window As IntPtr
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim match As TemplateMatch
Dim window As IntPtr
Dim returnValue As Rectangle

returnValue = match.ToScreenCoordinates(window)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Rectangle ToScreenCoordinates(
	TemplateMatch^ match, 
	IntPtr window
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToScreenCoordinates : 
        match : TemplateMatch * 
        window : IntPtr -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>match</dt><dd>Type: TemplateMatch<br />The source TemplateMatch.</dd><dt>window</dt><dd>Type: System.IntPtr<br />A handle to the window that belongs the source TemplateMatch.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting Rectangle.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TemplateMatch. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_AForge_Extensions_TemplateMatch_TemplateMatchExtensions">TemplateMatchExtensions Class</a><br /><a href="N_DevCase_ThirdParty_AForge_Extensions_TemplateMatch">DevCase.ThirdParty.AForge.Extensions.TemplateMatch Namespace</a><br />