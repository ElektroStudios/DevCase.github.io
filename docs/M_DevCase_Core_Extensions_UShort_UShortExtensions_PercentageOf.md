# UShortExtensions.PercentageOf Method 
 

Given a total number, calculates which percentage of is the source value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_UShort">DevCase.Core.Extensions.UShort</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static double PercentageOf(
	this ushort sender,
	double total
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function PercentageOf ( 
	sender As UShort,
	total As Double
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim sender As UShort
Dim total As Double
Dim returnValue As Double

returnValue = sender.PercentageOf(total)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static double PercentageOf(
	unsigned short sender, 
	double total
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member PercentageOf : 
        sender : uint16 * 
        total : float -> float 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.UInt16<br />The source value.</dd><dt>total</dt><dd>Type: System.Double<br />The total value.</dd></dl>

#### Return Value
Type: Double<br />The percentage value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type UInt16. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As UShort = CUShort(10US.PercentageOf(50US))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_UShort_UShortExtensions">UShortExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_UShort">DevCase.Core.Extensions.UShort Namespace</a><br />