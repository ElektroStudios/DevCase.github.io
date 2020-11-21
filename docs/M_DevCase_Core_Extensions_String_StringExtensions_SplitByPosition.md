# StringExtensions.SplitByPosition Method 
 

Split a String into two parts by the specified character position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<string> SplitByPosition(
	this string sender,
	int position
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function SplitByPosition ( 
	sender As String,
	position As Integer
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim position As Integer
Dim returnValue As IEnumerable(Of String)

returnValue = sender.SplitByPosition(position)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<String^>^ SplitByPosition(
	String^ sender, 
	int position
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SplitByPosition : 
        sender : string * 
        position : int -> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>position</dt><dd>Type: System.Int32<br />The starting character position where to split.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the parts of the splitted striing.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>Value bigger than 0 is required.;position</td></tr><tr><td>ArgumentOutOfRangeException</td><td>Value smaller than the source string length is required.;position</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim parts As IEnumerable(Of String) = "Hello World".SplitByPosition(4)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />