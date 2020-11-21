# EnumExtensions.ForEachFlag(*T*) Method 
 

Performs the specified action for each flag of the source enumeration.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Enum">DevCase.Core.Extensions.Enum</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void ForEachFlag<T>(
	this Enum sender,
	Action<T> action
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub ForEachFlag(Of T) ( 
	sender As Enum,
	action As Action(Of T)
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As Enum
Dim action As Action(Of T)

sender.ForEachFlag(action)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static void ForEachFlag(
	Enum^ sender, 
	Action<T>^ action
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ForEachFlag : 
        sender : Enum * 
        action : Action<'T> -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Enum<br />The source Enum.</dd><dt>action</dt><dd>Type: System.Action(*T*)<br />The Action to perform on each flag.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Enum. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim flags As FileAttributes = FileAttributes.ReadOnly Or FileAttributes.Hidden Or FileAttributes.System

flags.ForEachFlag(Of FileAttributes)(
    Sub(ByVal x As FileAttributes)
        MsgBox(x.ToString())
    End Sub)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Enum_EnumExtensions">EnumExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Enum">DevCase.Core.Extensions.Enum Namespace</a><br />