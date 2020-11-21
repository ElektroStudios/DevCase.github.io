# DecimalExtensions.IsMultipleOf Method 
 

Determines whether the source value is a multiple of the given value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Decimal">DevCase.Core.Extensions.Decimal</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsMultipleOf(
	this decimal sender,
	double value
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsMultipleOf ( 
	sender As Decimal,
	value As Double
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As Decimal
Dim value As Double
Dim returnValue As Boolean

returnValue = sender.IsMultipleOf(value)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsMultipleOf(
	Decimal sender, 
	double value
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsMultipleOf : 
        sender : decimal * 
        value : float -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Decimal<br />The source value.</dd><dt>value</dt><dd>Type: System.Double<br />The value.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the value is a multiple, `false` (`False` in Visual Basic) otherwise.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Decimal. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = 10D.IsMultipleOf(5D)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Decimal_DecimalExtensions">DecimalExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Decimal">DevCase.Core.Extensions.Decimal Namespace</a><br />