# ArrayExtensions.InvokeRepeat Method (Action, Int32)
 

Repeteadly invokes for the specified amount of times the method that the source Action encapsulates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void InvokeRepeat(
	this Action action,
	int count
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<ExtensionAttribute>
Public Shared Sub InvokeRepeat ( 
	action As Action,
	count As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim action As Action
Dim count As Integer

action.InvokeRepeat(count)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[ExtensionAttribute]
static void InvokeRepeat(
	Action^ action, 
	int count
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<ExtensionAttribute>]
static member InvokeRepeat : 
        action : Action * 
        count : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>action</dt><dd>Type: System.Action<br />The source Action.</dd><dt>count</dt><dd>Type: System.Int32<br />The amount of times to invoke the method that the source Action encapsulates.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Action. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>Value greater than zero is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Action_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Action_ArrayExtensions_InvokeRepeat">InvokeRepeat Overload</a><br /><a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action Namespace</a><br />