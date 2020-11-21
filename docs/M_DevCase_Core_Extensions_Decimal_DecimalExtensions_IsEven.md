# DecimalExtensions.IsEven Method 
 

Determines whether the value is a even number.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Decimal">DevCase.Core.Extensions.Decimal</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsEven(
	this decimal sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsEven ( 
	sender As Decimal
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As Decimal
Dim returnValue As Boolean

returnValue = sender.IsEven()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsEven(
	Decimal sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsEven : 
        sender : decimal -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Decimal<br />The source value.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the value is a even number, `false` (`False` in Visual Basic) otherwise.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Decimal. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = 10D.IsEven()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Decimal_DecimalExtensions">DecimalExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Decimal">DevCase.Core.Extensions.Decimal Namespace</a><br />