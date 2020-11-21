# EnumExtensions.Flags(*T*) Method 
 

Gets the current flags of the source enumeration.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Enum">DevCase.Core.Extensions.Enum</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T[] Flags<T>(
	this Enum sender
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function Flags(Of T) ( 
	sender As Enum
) As T()
```

**VB Usage**<br />
``` VB Usage
Dim sender As Enum
Dim returnValue As T()

returnValue = sender.Flags()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static array<T>^ Flags(
	Enum^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Flags : 
        sender : Enum -> 'T[] 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Enum<br />The source Enum.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*[]<br />The current flags.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Enum. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As FileAttributes = FileAttributes.ReadOnly Or FileAttributes.Hidden Or FileAttributes.System
Dim flags As FileAttributes() = value.Flags(Of FileAttributes)

For Each flag As FileAttributes In flags
    MsgBox(flag.ToString())
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Enum_EnumExtensions">EnumExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Enum">DevCase.Core.Extensions.Enum Namespace</a><br />