# SingleExtensions.FractionBy Method 
 

Takes a fraction of the source value that corresponds to the given percent value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Single">DevCase.Core.Extensions.Single</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static double FractionBy(
	this float sender,
	double percentage
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function FractionBy ( 
	sender As Single,
	percentage As Double
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim sender As Single
Dim percentage As Double
Dim returnValue As Double

returnValue = sender.FractionBy(percentage)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static double FractionBy(
	float sender, 
	double percentage
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FractionBy : 
        sender : float32 * 
        percentage : float -> float 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Single<br />The source value.</dd><dt>percentage</dt><dd>Type: System.Double<br />The percentage to fractionize by.</dd></dl>

#### Return Value
Type: Double<br />The fraction value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Single. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As Single = CSng(10.0F.FractionBy(50.0F))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Single_SingleExtensions">SingleExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Single">DevCase.Core.Extensions.Single Namespace</a><br />