# LongExtensions.ToCSharpHex Method 
 

Converts a value to its C# literal Hexadecimal representation.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Long">DevCase.Core.Extensions.Long</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ToCSharpHex(
	this long sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToCSharpHex ( 
	sender As Long
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Long
Dim returnValue As String

returnValue = sender.ToCSharpHex()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ToCSharpHex(
	long long sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToCSharpHex : 
        sender : int64 -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Int64<br />The source value.</dd></dl>

#### Return Value
Type: String<br />The Hexadecimal value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Int64. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim csharpHex As String = 10L.ToCSharpHex()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Long_LongExtensions">LongExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Long">DevCase.Core.Extensions.Long Namespace</a><br />