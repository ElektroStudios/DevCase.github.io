# HtmlDocumentExtensions.GetElementsByClassName Method 
 

Retrieve a collection of elements with the specified class name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_HtmlDocument">DevCase.Core.Extensions.HtmlDocument</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ReadOnlyCollection<HtmlElement> GetElementsByClassName(
	this HtmlDocument document,
	string className
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetElementsByClassName ( 
	document As HtmlDocument,
	className As String
) As ReadOnlyCollection(Of HtmlElement)
```

**VB Usage**<br />
``` VB Usage
Dim document As HtmlDocument
Dim className As String
Dim returnValue As ReadOnlyCollection(Of HtmlElement)

returnValue = document.GetElementsByClassName(className)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ReadOnlyCollection<HtmlElement^>^ GetElementsByClassName(
	HtmlDocument^ document, 
	String^ className
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetElementsByClassName : 
        document : HtmlDocument * 
        className : string -> ReadOnlyCollection<HtmlElement> 

```


#### Parameters
&nbsp;<dl><dt>document</dt><dd>Type: System.Windows.Forms.HtmlDocument<br />The source HtmlDocument.</dd><dt>className</dt><dd>Type: System.String<br />The class name.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(HtmlElement)<br />The resulting ReadOnlyCollection(T) collection.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type HtmlDocument. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_HtmlDocument_HtmlDocumentExtensions">HtmlDocumentExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_HtmlDocument">DevCase.Core.Extensions.HtmlDocument Namespace</a><br />