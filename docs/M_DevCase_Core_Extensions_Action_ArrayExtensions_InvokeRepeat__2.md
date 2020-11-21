# ArrayExtensions.InvokeRepeat(*T1*, *T2*) Method (Action(*T1*, *T2*), *T1*, *T2*, Int32)
 

Repeteadly invokes for the specified amount of times the method that the source Action encapsulates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void InvokeRepeat<T1, T2>(
	this Action<T1, T2> action,
	T1 arg1,
	T2 arg2,
	int count
)

```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<ExtensionAttribute>
Public Shared Sub InvokeRepeat(Of T1, T2) ( 
	action As Action(Of T1, T2),
	arg1 As T1,
	arg2 As T2,
	count As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim action As Action(Of T1, T2)
Dim arg1 As T1
Dim arg2 As T2
Dim count As Integer

action.InvokeRepeat(arg1, arg2, count)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[ExtensionAttribute]
generic<typename T1, typename T2>
static void InvokeRepeat(
	Action<T1, T2>^ action, 
	T1 arg1, 
	T2 arg2, 
	int count
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<ExtensionAttribute>]
static member InvokeRepeat : 
        action : Action<'T1, 'T2> * 
        arg1 : 'T1 * 
        arg2 : 'T2 * 
        count : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>action</dt><dd>Type: System.Action(*T1*, *T2*)<br />The source Action.</dd><dt>arg1</dt><dd>Type: *T1*<br />The first parameter of the method that the source Action encapsulates.</dd><dt>arg2</dt><dd>Type: *T2*<br />The second parameter of the method that the source Action encapsulates.</dd><dt>count</dt><dd>Type: System.Int32<br />The amount of times to invoke the method that the source Action encapsulates.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T1</dt><dd>The type of the first parameter of the method that the source Action encapsulates.</dd><dt>T2</dt><dd>The type of the second parameter of the method that the source Action encapsulates.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Action(*T1*, *T2*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>Value greater than zero is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Action_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Action_ArrayExtensions_InvokeRepeat">InvokeRepeat Overload</a><br /><a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action Namespace</a><br />