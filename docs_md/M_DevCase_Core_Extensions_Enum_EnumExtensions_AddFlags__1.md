# EnumExtensions.AddFlags(*T*) Method 
 

Adds the specified flags into a flags combination of the source enumeration.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Enum">DevCase.Core.Extensions.Enum</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T AddFlags<T>(
	this Enum sender,
	params T[] flags
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AddFlags(Of T) ( 
	sender As Enum,
	ParamArray flags As T()
) As T
```

**VB Usage**<br />
``` VB Usage
Dim sender As Enum
Dim flags As T()
Dim returnValue As T

returnValue = sender.AddFlags(flags)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static T AddFlags(
	Enum^ sender, 
	... array<T>^ flags
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AddFlags : 
        sender : Enum * 
        flags : 'T[] -> 'T 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Enum<br />The source Enum.</dd><dt>flags</dt><dd>Type: *T*[]<br />The flags to add.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*<br />The resulting flags combination.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Enum. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim flags As FileAttributes = FileAttributes.ReadOnly Or FileAttributes.Hidden
flags = flags.AddFlags({FileAttributes.Compressed, FileAttributes.Encrypted})

MsgBox(flags.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Enum_EnumExtensions">EnumExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Enum">DevCase.Core.Extensions.Enum Namespace</a><br />