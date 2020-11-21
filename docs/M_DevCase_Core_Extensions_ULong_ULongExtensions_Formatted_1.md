# ULongExtensions.Formatted Method (UInt64, Int32)
 

Formats a value by placing dots or commas in the corresponding positions depending on the specified culture.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ULong">DevCase.Core.Extensions.ULong</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Formatted(
	this ulong sender,
	int precision
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Formatted ( 
	sender As ULong,
	precision As Integer
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As ULong
Dim precision As Integer
Dim returnValue As String

returnValue = sender.Formatted(precision)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Formatted(
	unsigned long long sender, 
	int precision
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Formatted : 
        sender : uint64 * 
        precision : int -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.UInt64<br />The source value.</dd><dt>precision</dt><dd>Type: System.Int32<br />The decimals precision.</dd></dl>

#### Return Value
Type: String<br />The formatted value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type UInt64. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim number As String = 10000UL.Formatted(precision:=0)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ULong_ULongExtensions">ULongExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_ULong_ULongExtensions_Formatted">Formatted Overload</a><br /><a href="N_DevCase_Core_Extensions_ULong">DevCase.Core.Extensions.ULong Namespace</a><br />