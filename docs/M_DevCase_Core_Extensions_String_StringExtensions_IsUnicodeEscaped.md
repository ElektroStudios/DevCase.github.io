# StringExtensions.IsUnicodeEscaped Method 
 

Determines whether the source string contains Unicode escape sequences.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsUnicodeEscaped(
	this string sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsUnicodeEscaped ( 
	sender As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim returnValue As Boolean

returnValue = sender.IsUnicodeEscaped()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsUnicodeEscaped(
	String^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsUnicodeEscaped : 
        sender : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source string.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the string contains Unicode escape sequences, otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isUnicodeEscaped As Boolean = "\u0048\u0065\u006C\u006C\u006F".IsUnicodeEscaped()

MessageBox.Show(isUnicodeEscaped)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />