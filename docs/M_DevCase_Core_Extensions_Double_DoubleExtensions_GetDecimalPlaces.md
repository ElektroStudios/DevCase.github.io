# DoubleExtensions.GetDecimalPlaces Method 
 

Returns the number of decimal places for the specified value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Double">DevCase.Core.Extensions.Double</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int GetDecimalPlaces(
	this double value
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetDecimalPlaces ( 
	value As Double
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim value As Double
Dim returnValue As Integer

returnValue = value.GetDecimalPlaces()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int GetDecimalPlaces(
	double value
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetDecimalPlaces : 
        value : float -> int 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.Double<br />The source value.</dd></dl>

#### Return Value
Type: Int32<br />The number of decimal places for the specified value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Double. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As Double = 0.12345
Dim decimalPlaces As Integer = GetDecimalPlaces(value)
Console.WriteLine(decimalPlaces)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Double_DoubleExtensions">DoubleExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Double">DevCase.Core.Extensions.Double Namespace</a><br />