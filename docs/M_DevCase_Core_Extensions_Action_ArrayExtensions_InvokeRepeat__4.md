# ArrayExtensions.InvokeRepeat(*T1*, *T2*, *T3*, *T4*) Method (Action(*T1*, *T2*, *T3*, *T4*), *T1*, *T2*, *T3*, *T4*, Int32)
 

Repeteadly invokes for the specified amount of times the method that the source Action encapsulates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void InvokeRepeat<T1, T2, T3, T4>(
	this Action<T1, T2, T3, T4> action,
	T1 arg1,
	T2 arg2,
	T3 arg3,
	T4 arg4,
	int count
)

```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<ExtensionAttribute>
Public Shared Sub InvokeRepeat(Of T1, T2, T3, T4) ( 
	action As Action(Of T1, T2, T3, T4),
	arg1 As T1,
	arg2 As T2,
	arg3 As T3,
	arg4 As T4,
	count As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim action As Action(Of T1, T2, T3, T4)
Dim arg1 As T1
Dim arg2 As T2
Dim arg3 As T3
Dim arg4 As T4
Dim count As Integer

action.InvokeRepeat(arg1, arg2, arg3, 
	arg4, count)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[ExtensionAttribute]
generic<typename T1, typename T2, typename T3, typename T4>
static void InvokeRepeat(
	Action<T1, T2, T3, T4>^ action, 
	T1 arg1, 
	T2 arg2, 
	T3 arg3, 
	T4 arg4, 
	int count
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<ExtensionAttribute>]
static member InvokeRepeat : 
        action : Action<'T1, 'T2, 'T3, 'T4> * 
        arg1 : 'T1 * 
        arg2 : 'T2 * 
        arg3 : 'T3 * 
        arg4 : 'T4 * 
        count : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>action</dt><dd>Type: System.Action(*T1*, *T2*, *T3*, *T4*)<br />The source Action.</dd><dt>arg1</dt><dd>Type: *T1*<br />The first parameter of the method that the source Action encapsulates.</dd><dt>arg2</dt><dd>Type: *T2*<br />The second parameter of the method that the source Action encapsulates.</dd><dt>arg3</dt><dd>Type: *T3*<br />The third parameter of the method that the source Action encapsulates.</dd><dt>arg4</dt><dd>Type: *T4*<br />The fourth parameter of the method that the source Action encapsulates.</dd><dt>count</dt><dd>Type: System.Int32<br />The amount of times to invoke the method that the source Action encapsulates.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T1</dt><dd>The type of the first parameter of the method that the source Action encapsulates.</dd><dt>T2</dt><dd>The type of the second parameter of the method that the source Action encapsulates.</dd><dt>T3</dt><dd>The type of the third parameter of the method that the source Action encapsulates.</dd><dt>T4</dt><dd>The type of the fourth parameter of the method that the source Action encapsulates.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Action(*T1*, *T2*, *T3*, *T4*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>Value greater than zero is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Action_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Action_ArrayExtensions_InvokeRepeat">InvokeRepeat Overload</a><br /><a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action Namespace</a><br />