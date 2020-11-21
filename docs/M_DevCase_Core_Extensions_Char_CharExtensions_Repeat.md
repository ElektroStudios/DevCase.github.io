# CharExtensions.Repeat Method 
 

Returns the source character repeated the specified amount of times.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Char">DevCase.Core.Extensions.Char</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Repeat(
	this char sender,
	int count
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Repeat ( 
	sender As Char,
	count As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Char
Dim count As Integer
Dim returnValue As String

returnValue = sender.Repeat(count)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Repeat(
	wchar_t sender, 
	int count
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Repeat : 
        sender : char * 
        count : int -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Char<br />The source character.</dd><dt>count</dt><dd>Type: System.Int32<br />The amount of times to repeat.</dd></dl>

#### Return Value
Type: String<br />The resulting string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Char. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = "A"c.Repeat(2)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Char_CharExtensions">CharExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Char">DevCase.Core.Extensions.Char Namespace</a><br />