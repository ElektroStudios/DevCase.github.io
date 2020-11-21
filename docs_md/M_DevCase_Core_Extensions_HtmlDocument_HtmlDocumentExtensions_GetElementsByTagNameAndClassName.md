# HtmlDocumentExtensions.GetElementsByTagNameAndClassName Method 
 

Retrieve a collection of elements with the specified HTML tag and class name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_HtmlDocument">DevCase.Core.Extensions.HtmlDocument</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ReadOnlyCollection<HtmlElement> GetElementsByTagNameAndClassName(
	this HtmlDocument document,
	string tagName,
	string className
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetElementsByTagNameAndClassName ( 
	document As HtmlDocument,
	tagName As String,
	className As String
) As ReadOnlyCollection(Of HtmlElement)
```

**VB Usage**<br />
``` VB Usage
Dim document As HtmlDocument
Dim tagName As String
Dim className As String
Dim returnValue As ReadOnlyCollection(Of HtmlElement)

returnValue = document.GetElementsByTagNameAndClassName(tagName, 
	className)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ReadOnlyCollection<HtmlElement^>^ GetElementsByTagNameAndClassName(
	HtmlDocument^ document, 
	String^ tagName, 
	String^ className
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetElementsByTagNameAndClassName : 
        document : HtmlDocument * 
        tagName : string * 
        className : string -> ReadOnlyCollection<HtmlElement> 

```


#### Parameters
&nbsp;<dl><dt>document</dt><dd>Type: System.Windows.Forms.HtmlDocument<br />The source HtmlDocument.</dd><dt>tagName</dt><dd>Type: System.String<br />The HTML tag.</dd><dt>className</dt><dd>Type: System.String<br />The class name.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(HtmlElement)<br />The resulting ReadOnlyCollection(T) collection.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type HtmlDocument. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_HtmlDocument_HtmlDocumentExtensions">HtmlDocumentExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_HtmlDocument">DevCase.Core.Extensions.HtmlDocument Namespace</a><br />