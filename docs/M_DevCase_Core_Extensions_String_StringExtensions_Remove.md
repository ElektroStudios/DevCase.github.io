# StringExtensions.Remove Method 
 

Removes characters from the source string, based on a predicate.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Remove(
	this string str,
	Func<char, bool> predicate
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Remove ( 
	str As String,
	predicate As Func(Of Char, Boolean)
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim predicate As Func(Of Char, Boolean)
Dim returnValue As String

returnValue = str.Remove(predicate)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Remove(
	String^ str, 
	Func<wchar_t, bool>^ predicate
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Remove : 
        str : string * 
        predicate : Func<char, bool> -> string 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The source string.</dd><dt>predicate</dt><dd>Type: System.Func(Char, Boolean)<br />A function to test each character for a removal condition.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "Hello World!"
' Remove punctuation characters from the source string.
Dim clean As String = str.Remove(Function(c As Char) Char.IsPunctuation(c))

Console.WriteLine(clean)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />