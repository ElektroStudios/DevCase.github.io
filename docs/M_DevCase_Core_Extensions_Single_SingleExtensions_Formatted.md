# SingleExtensions.Formatted Method (Single)
 

Formats a value by placing dots or commas in the corresponding positions depending on the specified culture.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Single">DevCase.Core.Extensions.Single</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string Formatted(
	this float sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Formatted ( 
	sender As Single
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Single
Dim returnValue As String

returnValue = sender.Formatted()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ Formatted(
	float sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Formatted : 
        sender : float32 -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Single<br />The source value.</dd></dl>

#### Return Value
Type: String<br />The formatted value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Single. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim number As String = 10000.0F.Formatted()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Single_SingleExtensions">SingleExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Single_SingleExtensions_Formatted">Formatted Overload</a><br /><a href="N_DevCase_Core_Extensions_Single">DevCase.Core.Extensions.Single Namespace</a><br />