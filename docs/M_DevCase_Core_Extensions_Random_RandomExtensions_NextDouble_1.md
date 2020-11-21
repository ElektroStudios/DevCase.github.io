# RandomExtensions.NextDouble Method (Random, Double, Double)
 

Returns a non-negative Double value between the minimum and maximum specified.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Random">DevCase.Core.Extensions.Random</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static double NextDouble(
	this Random sender,
	double minValue,
	double maxValue
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function NextDouble ( 
	sender As Random,
	minValue As Double,
	maxValue As Double
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim sender As Random
Dim minValue As Double
Dim maxValue As Double
Dim returnValue As Double

returnValue = sender.NextDouble(minValue, 
	maxValue)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static double NextDouble(
	Random^ sender, 
	double minValue, 
	double maxValue
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member NextDouble : 
        sender : Random * 
        minValue : float * 
        maxValue : float -> float 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Random<br />The source Random.</dd><dt>minValue</dt><dd>Type: System.Double<br />The minimum value.</dd><dt>maxValue</dt><dd>Type: System.Double<br />The maximum value.</dd></dl>

#### Return Value
Type: Double<br />The resulting Double value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Random. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Random_RandomExtensions">RandomExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Random_RandomExtensions_NextDouble">NextDouble Overload</a><br /><a href="N_DevCase_Core_Extensions_Random">DevCase.Core.Extensions.Random Namespace</a><br />