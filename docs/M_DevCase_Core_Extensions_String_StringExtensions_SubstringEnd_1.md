# StringExtensions.SubstringEnd Method (String, Int32, Int32)
 

Retrieves a substring from the source String. 

 The substring starts at the end of the string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string SubstringEnd(
	this string source,
	int startIndex,
	int length
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function SubstringEnd ( 
	source As String,
	startIndex As Integer,
	length As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim source As String
Dim startIndex As Integer
Dim length As Integer
Dim returnValue As String

returnValue = source.SubstringEnd(startIndex, 
	length)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ SubstringEnd(
	String^ source, 
	int startIndex, 
	int length
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SubstringEnd : 
        source : string * 
        startIndex : int * 
        length : int -> string 

```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: System.String<br />The source String.</dd><dt>startIndex</dt><dd>Type: System.Int32<br />The zero-based starting character position of the substring.</dd><dt>length</dt><dd>Type: System.Int32<br />The number of characters in the substring.</dd></dl>

#### Return Value
Type: String<br />The resulting substring.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello World".SubstringEnd(2, 2)

MessageBox.Show(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_String_StringExtensions_SubstringEnd">SubstringEnd Overload</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />