# RandomExtensions.NextSingle Method (Random)
 

Returns a non-negative Single value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Random">DevCase.Core.Extensions.Random</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static float NextSingle(
	this Random sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function NextSingle ( 
	sender As Random
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim sender As Random
Dim returnValue As Single

returnValue = sender.NextSingle()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static float NextSingle(
	Random^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member NextSingle : 
        sender : Random -> float32 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Random<br />The source Random.</dd></dl>

#### Return Value
Type: Single<br />The resulting Single value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Random. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Random_RandomExtensions">RandomExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Random_RandomExtensions_NextSingle">NextSingle Overload</a><br /><a href="N_DevCase_Core_Extensions_Random">DevCase.Core.Extensions.Random Namespace</a><br />