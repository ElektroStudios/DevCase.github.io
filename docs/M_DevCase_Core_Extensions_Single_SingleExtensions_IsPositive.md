# SingleExtensions.IsPositive Method 
 

Determines whether the value is a positive number.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Single">DevCase.Core.Extensions.Single</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsPositive(
	this float sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsPositive ( 
	sender As Single
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As Single
Dim returnValue As Boolean

returnValue = sender.IsPositive()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsPositive(
	float sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsPositive : 
        sender : float32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Single<br />The source value.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the value is a positive number, `false` (`False` in Visual Basic) otherwise.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Single. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = 10.0F.IsPositive()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Single_SingleExtensions">SingleExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Single">DevCase.Core.Extensions.Single Namespace</a><br />