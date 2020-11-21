# DoubleExtensions.DifferenceOf Method 
 

Gets the difference between the source value and the specified value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Double">DevCase.Core.Extensions.Double</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static double DifferenceOf(
	this double sender,
	double value
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function DifferenceOf ( 
	sender As Double,
	value As Double
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim sender As Double
Dim value As Double
Dim returnValue As Double

returnValue = sender.DifferenceOf(value)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static double DifferenceOf(
	double sender, 
	double value
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DifferenceOf : 
        sender : float * 
        value : float -> float 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Double<br />The source value.</dd><dt>value</dt><dd>Type: System.Double<br />The value.</dd></dl>

#### Return Value
Type: Double<br />The difference.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Double. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As Double = 10.DifferenceOf(100)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Double_DoubleExtensions">DoubleExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Double">DevCase.Core.Extensions.Double Namespace</a><br />