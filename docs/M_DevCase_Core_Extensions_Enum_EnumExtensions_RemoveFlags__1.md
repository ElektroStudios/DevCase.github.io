# EnumExtensions.RemoveFlags(*T*) Method 
 

Removes the specified flags from a flags combination of the source enumeration.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Enum">DevCase.Core.Extensions.Enum</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T RemoveFlags<T>(
	this Enum sender,
	params T[] flags
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function RemoveFlags(Of T) ( 
	sender As Enum,
	ParamArray flags As T()
) As T
```

**VB Usage**<br />
``` VB Usage
Dim sender As Enum
Dim flags As T()
Dim returnValue As T

returnValue = sender.RemoveFlags(flags)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static T RemoveFlags(
	Enum^ sender, 
	... array<T>^ flags
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RemoveFlags : 
        sender : Enum * 
        flags : 'T[] -> 'T 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Enum<br />The source Enum.</dd><dt>flags</dt><dd>Type: *T*[]<br />The flags to remove.</dd></dl>

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
Dim flags As FileAttributes = FileAttributes.ReadOnly Or FileAttributes.Hidden Or FileAttributes.System
flags = flags.RemoveFlags({FileAttributes.ReadOnly, FileAttributes.System})

MsgBox(flags.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Enum_EnumExtensions">EnumExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Enum">DevCase.Core.Extensions.Enum Namespace</a><br />