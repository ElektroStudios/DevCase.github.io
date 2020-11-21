# IWebElementExtensions.SetAttribute Method 
 

Sets the value of the specified attribute for the source element.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebElement">DevCase.ThirdParty.Selenium.Extensions.IWebElement</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetAttribute(
	this IWebElement element,
	string attributeName,
	string value
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetAttribute ( 
	element As IWebElement,
	attributeName As String,
	value As String
)
```

**VB Usage**<br />
``` VB Usage
Dim element As IWebElement
Dim attributeName As String
Dim value As String

element.SetAttribute(attributeName, 
	value)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetAttribute(
	IWebElement^ element, 
	String^ attributeName, 
	String^ value
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetAttribute : 
        element : IWebElement * 
        attributeName : string * 
        value : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>element</dt><dd>Type: IWebElement<br />The source IWebElement.</dd><dt>attributeName</dt><dd>Type: System.String<br />The name of the attribute.</dd><dt>value</dt><dd>Type: System.String<br />The new value.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWebElement. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_IWebElement_IWebElementExtensions">IWebElementExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebElement">DevCase.ThirdParty.Selenium.Extensions.IWebElement Namespace</a><br />