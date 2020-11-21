# UShortExtensions.IsDivisibleBy Method 
 

Determines whether the source value is divisible by the given value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_UShort">DevCase.Core.Extensions.UShort</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsDivisibleBy(
	this ushort sender,
	double value
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsDivisibleBy ( 
	sender As UShort,
	value As Double
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As UShort
Dim value As Double
Dim returnValue As Boolean

returnValue = sender.IsDivisibleBy(value)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsDivisibleBy(
	unsigned short sender, 
	double value
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsDivisibleBy : 
        sender : uint16 * 
        value : float -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.UInt16<br />The source value.</dd><dt>value</dt><dd>Type: System.Double<br />The value to divide by.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the value is divisible, `false` (`False` in Visual Basic) otherwise.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type UInt16. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = 10US.IsDivisibleBy(5US)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_UShort_UShortExtensions">UShortExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_UShort">DevCase.Core.Extensions.UShort Namespace</a><br />