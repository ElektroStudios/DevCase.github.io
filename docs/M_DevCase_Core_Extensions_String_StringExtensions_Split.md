# StringExtensions.Split Method (String, String, Int32, StringSplitOptions)
 

Splits a string into a maximum number of substrings based on the specified string. 

 You can specify whether the substrings include empty array elements.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string[] Split(
	this string sender,
	string separator,
	int count,
	StringSplitOptions options
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Split ( 
	sender As String,
	separator As String,
	count As Integer,
	options As StringSplitOptions
) As String()
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim separator As String
Dim count As Integer
Dim options As StringSplitOptions
Dim returnValue As String()

returnValue = sender.Split(separator, 
	count, options)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static array<String^>^ Split(
	String^ sender, 
	String^ separator, 
	int count, 
	StringSplitOptions options
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Split : 
        sender : string * 
        separator : string * 
        count : int * 
        options : StringSplitOptions -> string[] 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>separator</dt><dd>Type: System.String<br />A string that delimits the substrings in this string.</dd><dt>count</dt><dd>Type: System.Int32<br />The maximum number of substrings to return.</dd><dt>options</dt><dd>Type: System.StringSplitOptions<br />RemoveEmptyEntries to omit empty array elements from the array returned. 

None to include empty array elements in the array returned.</dd></dl>

#### Return Value
Type: String[]<br />A String array whose elements contain the substrings from this instance that are delimited by the specified string in *separator*.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello" & Environment.NewLine & Environment.NewLine & "World"
Dim arr As String() = str.Split(ControlChars.NewLine, 3, StringSplitOptions.None)
For Each item As String In arr
    Console.WriteLine(item)
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_Split">Split Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />