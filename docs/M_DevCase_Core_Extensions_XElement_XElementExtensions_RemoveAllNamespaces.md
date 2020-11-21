# XElementExtensions.RemoveAllNamespaces Method 
 

Removes all namespaces on the source XElement.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XElement">DevCase.Core.Extensions.XElement</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static XElement RemoveAllNamespaces(
	this XElement sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function RemoveAllNamespaces ( 
	sender As XElement
) As XElement
```

**VB Usage**<br />
``` VB Usage
Dim sender As XElement
Dim returnValue As XElement

returnValue = sender.RemoveAllNamespaces()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static XElement^ RemoveAllNamespaces(
	XElement^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RemoveAllNamespaces : 
        sender : XElement -> XElement 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Xml.Linq.XElement<br />The source XElement.</dd></dl>

#### Return Value
Type: XElement<br />The resulting XElement.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type XElement. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim element As XElement = XElement.Parse("abc def ghi")
Dim elementWithoutNamespaces As XElement = element.RemoveAllNamespaces()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XElement_XElementExtensions">XElementExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_XElement">DevCase.Core.Extensions.XElement Namespace</a><br />