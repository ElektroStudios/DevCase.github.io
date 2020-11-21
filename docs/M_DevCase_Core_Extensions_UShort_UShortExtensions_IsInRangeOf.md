# UShortExtensions.IsInRangeOf Method 
 

Determines whether the source value is in range of the given *min* and *max* values.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_UShort">DevCase.Core.Extensions.UShort</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsInRangeOf(
	this ushort sender,
	double min,
	double max
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsInRangeOf ( 
	sender As UShort,
	min As Double,
	max As Double
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As UShort
Dim min As Double
Dim max As Double
Dim returnValue As Boolean

returnValue = sender.IsInRangeOf(min, 
	max)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsInRangeOf(
	unsigned short sender, 
	double min, 
	double max
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsInRangeOf : 
        sender : uint16 * 
        min : float * 
        max : float -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.UInt16<br />The source value.</dd><dt>min</dt><dd>Type: System.Double<br />The minimum value of the range.</dd><dt>max</dt><dd>Type: System.Double<br />The maximum value of the range.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the value is in range, `false` (`False` in Visual Basic) otherwise.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type UInt16. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = 10US.IsInRangeOf(min:=1US, max:=100US)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_UShort_UShortExtensions">UShortExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_UShort">DevCase.Core.Extensions.UShort Namespace</a><br />