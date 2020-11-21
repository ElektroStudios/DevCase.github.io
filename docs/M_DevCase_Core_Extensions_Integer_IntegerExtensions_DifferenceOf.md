# IntegerExtensions.DifferenceOf Method 
 

Gets the difference between the source value and the specified value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Integer">DevCase.Core.Extensions.Integer</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static double DifferenceOf(
	this int sender,
	double value
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function DifferenceOf ( 
	sender As Integer,
	value As Double
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim sender As Integer
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
	int sender, 
	double value
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DifferenceOf : 
        sender : int * 
        value : float -> float 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Int32<br />The source value.</dd><dt>value</dt><dd>Type: System.Double<br />The value.</dd></dl>

#### Return Value
Type: Double<br />The difference.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Int32. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As Integer = CInt(10I.DifferenceOf(100I))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Integer_IntegerExtensions">IntegerExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Integer">DevCase.Core.Extensions.Integer Namespace</a><br />