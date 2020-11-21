# BooleanExtensions.ToBit Method 
 

Returns the binary representation of the specified Boolean value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Boolean">DevCase.Core.Extensions.Boolean</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static int ToBit(
	this bool sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToBit ( 
	sender As Boolean
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim sender As Boolean
Dim returnValue As Integer

returnValue = sender.ToBit()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static int ToBit(
	bool sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToBit : 
        sender : bool -> int 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Boolean<br />The source Boolean.</dd></dl>

#### Return Value
Type: Int32<br />If the Boolean value is `true` (`True` in Visual Basic), `1` (one); otherwise, `0` (zero).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Boolean. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim bit As Integer = (True).ToBit()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Boolean_BooleanExtensions">BooleanExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Boolean">DevCase.Core.Extensions.Boolean Namespace</a><br />