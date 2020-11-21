# EnumExtensions.HasFlagsAttribute Method 
 

Determines whether the specified enumeration is declared with FlagsAttribute.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Enum">DevCase.Core.Extensions.Enum</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool HasFlagsAttribute(
	this Enum sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function HasFlagsAttribute ( 
	sender As Enum
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As Enum
Dim returnValue As Boolean

returnValue = sender.HasFlagsAttribute()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool HasFlagsAttribute(
	Enum^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member HasFlagsAttribute : 
        sender : Enum -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Enum<br />The source Enum.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified enumeration is declared with FlagsAttribute; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Enum. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = (New FileAttributes).HasFlagsAttribute()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Enum_EnumExtensions">EnumExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Enum">DevCase.Core.Extensions.Enum Namespace</a><br />