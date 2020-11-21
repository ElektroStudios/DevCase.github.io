# XElementExtensions.SortByElement Method 
 

Sorts an IEnumerable(T) by the specified element.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XElement">DevCase.Core.Extensions.XElement</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<XElement> SortByElement(
	this IEnumerable<XElement> sender,
	string elementName
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function SortByElement ( 
	sender As IEnumerable(Of XElement),
	elementName As String
) As IEnumerable(Of XElement)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of XElement)
Dim elementName As String
Dim returnValue As IEnumerable(Of XElement)

returnValue = sender.SortByElement(elementName)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<XElement^>^ SortByElement(
	IEnumerable<XElement^>^ sender, 
	String^ elementName
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SortByElement : 
        sender : IEnumerable<XElement> * 
        elementName : string -> IEnumerable<XElement> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(XElement)<br />The source IEnumerable(T).</dd><dt>elementName</dt><dd>Type: System.String<br />The element name to sort by.</dd></dl>

#### Return Value
Type: IEnumerable(XElement)<br />The sorted IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(XElement). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim xml As String =
    <Songs>
        <Song><Name>My Song 3.mp3</Name></Song>
        <Song><Name>My Song 1.mp3</Name></Song>
        <Song><Name>My Song 2.mp3</Name></Song>
    </Songs>.ToString()

Dim xmlDoc As New XmlDocument
xmlDoc.LoadXml(xml)

xmlDoc = xmlDoc.SortByElement(rootElementName:="Song", elementName:="Name")
MessageBox.Show(xmlDoc.InnerXml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XElement_XElementExtensions">XElementExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_XElement">DevCase.Core.Extensions.XElement Namespace</a><br />