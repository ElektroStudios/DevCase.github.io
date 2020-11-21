# StringExtensions.FindExact Method 
 

Finds the elements that are equals to the specified string on the source IEnumerable(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<string> FindExact(
	this IEnumerable<string> sender,
	string searchString,
	StringComparison stringComparison
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function FindExact ( 
	sender As IEnumerable(Of String),
	searchString As String,
	stringComparison As StringComparison
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sender As IEnumerable(Of String)
Dim searchString As String
Dim stringComparison As StringComparison
Dim returnValue As IEnumerable(Of String)

returnValue = sender.FindExact(searchString, 
	stringComparison)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<String^>^ FindExact(
	IEnumerable<String^>^ sender, 
	String^ searchString, 
	StringComparison stringComparison
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FindExact : 
        sender : IEnumerable<string> * 
        searchString : string * 
        stringComparison : StringComparison -> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The source collections.</dd><dt>searchString</dt><dd>Type: System.String<br />The string to search for.</dd><dt>stringComparison</dt><dd>Type: System.StringComparison<br />The string comparison rule.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />IEnumerable(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IEnumerable(String). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim col As IEnumerable(Of String) = {"Hello World !!", "a", "b", "c"}
Debug.WriteLine(String.Join(", ", col.FindExact(searchString:="a", stringComparison:=StringComparison.OrdinalIgnoreCase)))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />