# StringExtensions.CountNonEmptyItems Method 
 

Counts the non-empty items of an IEnumerable(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int CountNonEmptyItems(
	this IEnumerable<string> sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CountNonEmptyItems ( 
	sender As IEnumerable(Of String)
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of String)
Dim returnValue As Integer

returnValue = sender.CountNonEmptyItems()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int CountNonEmptyItems(
	IEnumerable<String^>^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CountNonEmptyItems : 
        sender : IEnumerable<string> -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The source IEnumerable(T).</dd></dl>

#### Return Value
Type: Int32<br />The total amount of non-empty items.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(String). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim nonEmptyLinesCount As Integer = {"Hello", "   ", "World!"}.CountNonEmptyItems
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />