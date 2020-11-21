# XmlDocumentExtensions.GetXPaths Method 
 

Gets a IEnumerable(T) collection with the available XPath expressions of an XmlDocument document.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XmlDocument">DevCase.Core.Extensions.XmlDocument</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<string> GetXPaths(
	this XmlDocument sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetXPaths ( 
	sender As XmlDocument
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sender As XmlDocument
Dim returnValue As IEnumerable(Of String)

returnValue = sender.GetXPaths()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<String^>^ GetXPaths(
	XmlDocument^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetXPaths : 
        sender : XmlDocument -> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Xml.XmlDocument<br />The source XmlDocument.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />A IEnumerable(T) collection with the available XPath expressions.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type XmlDocument. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

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

Dim xPathList As IEnumerable(Of String) = xmlDoc.GetXPaths
MessageBox.Show(String.Join(Environment.NewLine, xPathList))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XmlDocument_XmlDocumentExtensions">XmlDocumentExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_XmlDocument">DevCase.Core.Extensions.XmlDocument Namespace</a><br />