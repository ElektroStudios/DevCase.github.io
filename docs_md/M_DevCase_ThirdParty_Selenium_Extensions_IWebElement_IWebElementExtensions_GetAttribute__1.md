# IWebElementExtensions.GetAttribute(*T*) Method 
 

Gets the value of the specified attribute for the source element, and converts the value to the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebElement">DevCase.ThirdParty.Selenium.Extensions.IWebElement</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T GetAttribute<T>(
	this IWebElement element,
	string attributeName
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetAttribute(Of T) ( 
	element As IWebElement,
	attributeName As String
) As T
```

**VB Usage**<br />
``` VB Usage
Dim element As IWebElement
Dim attributeName As String
Dim returnValue As T

returnValue = element.GetAttribute(attributeName)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static T GetAttribute(
	IWebElement^ element, 
	String^ attributeName
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetAttribute : 
        element : IWebElement * 
        attributeName : string -> 'T 

```


#### Parameters
&nbsp;<dl><dt>element</dt><dd>Type: IWebElement<br />The source IWebElement.</dd><dt>attributeName</dt><dd>Type: System.String<br />The name of the attribute.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd /></dl>

#### Return Value
Type: *T*<br />The attribute's current value. Returns a null if the value is not set.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWebElement. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_IWebElement_IWebElementExtensions">IWebElementExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebElement">DevCase.ThirdParty.Selenium.Extensions.IWebElement Namespace</a><br />