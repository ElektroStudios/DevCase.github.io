# XElementExtensions.DistinctByElement Method 
 

Deletes duplicated values by the specified element of an IEnumerable(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XElement">DevCase.Core.Extensions.XElement</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<XElement> DistinctByElement(
	this IEnumerable<XElement> sender,
	string elementName
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function DistinctByElement ( 
	sender As IEnumerable(Of XElement),
	elementName As String
) As IEnumerable(Of XElement)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of XElement)
Dim elementName As String
Dim returnValue As IEnumerable(Of XElement)

returnValue = sender.DistinctByElement(elementName)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<XElement^>^ DistinctByElement(
	IEnumerable<XElement^>^ sender, 
	String^ elementName
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DistinctByElement : 
        sender : IEnumerable<XElement> * 
        elementName : string -> IEnumerable<XElement> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(XElement)<br />The source IEnumerable(T).</dd><dt>elementName</dt><dd>Type: System.String<br />The element name to remove its duplicated values.</dd></dl>

#### Return Value
Type: IEnumerable(XElement)<br />The IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(XElement). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim xDoc As XDocument =
    <?xml version="1.0" encoding="Windows-1252"?>
    <!--Xml Songs Database-->
    <Songs>
        <Song><Name>My Song 1.mp3</Name></Song>
        <Song><Name>My Song 1.mp3</Name></Song>
        <Song><Name>My Song 2.mp3</Name></Song>
    </Songs>

For Each el As XElement In xDoc.<Songs>.<Song>.DistinctByElement(elementName:="Name")
    MessageBox.Show(el.Value)
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XElement_XElementExtensions">XElementExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_XElement">DevCase.Core.Extensions.XElement Namespace</a><br />