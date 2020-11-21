# ArrayExtensions.InvokeRepeat(*T1*, *T2*, *T3*, *T4*, *T5*, *T6*, *T7*, *T8*, *T9*, *T10*, *T11*, *T12*, *T13*, *T14*, *T15*, *T16*) Method (Action(*T1*, *T2*, *T3*, *T4*, *T5*, *T6*, *T7*, *T8*, *T9*, *T10*, *T11*, *T12*, *T13*, *T14*, *T15*, *T16*), *T1*, *T2*, *T3*, *T4*, *T5*, *T6*, *T7*, *T8*, *T9*, *T10*, *T11*, *T12*, *T13*, *T14*, *T15*, *T16*, Int32)
 

Repeteadly invokes for the specified amount of times the method that the source Action encapsulates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void InvokeRepeat<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>(
	this Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16> action,
	T1 arg1,
	T2 arg2,
	T3 arg3,
	T4 arg4,
	T5 arg5,
	T6 arg6,
	T7 arg7,
	T8 arg8,
	T9 arg9,
	T10 arg10,
	T11 arg11,
	T12 arg12,
	T13 arg13,
	T14 arg14,
	T15 arg15,
	T16 arg16,
	int count
)

```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<ExtensionAttribute>
Public Shared Sub InvokeRepeat(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16) ( 
	action As Action(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16),
	arg1 As T1,
	arg2 As T2,
	arg3 As T3,
	arg4 As T4,
	arg5 As T5,
	arg6 As T6,
	arg7 As T7,
	arg8 As T8,
	arg9 As T9,
	arg10 As T10,
	arg11 As T11,
	arg12 As T12,
	arg13 As T13,
	arg14 As T14,
	arg15 As T15,
	arg16 As T16,
	count As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim action As Action(Of T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16)
Dim arg1 As T1
Dim arg2 As T2
Dim arg3 As T3
Dim arg4 As T4
Dim arg5 As T5
Dim arg6 As T6
Dim arg7 As T7
Dim arg8 As T8
Dim arg9 As T9
Dim arg10 As T10
Dim arg11 As T11
Dim arg12 As T12
Dim arg13 As T13
Dim arg14 As T14
Dim arg15 As T15
Dim arg16 As T16
Dim count As Integer

action.InvokeRepeat(arg1, arg2, arg3, 
	arg4, arg5, arg6, arg7, arg8, arg9, 
	arg10, arg11, arg12, arg13, arg14, 
	arg15, arg16, count)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[ExtensionAttribute]
generic<typename T1, typename T2, typename T3, typename T4, typename T5, typename T6, typename T7, typename T8, typename T9, typename T10, typename T11, typename T12, typename T13, typename T14, typename T15, typename T16>
static void InvokeRepeat(
	Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>^ action, 
	T1 arg1, 
	T2 arg2, 
	T3 arg3, 
	T4 arg4, 
	T5 arg5, 
	T6 arg6, 
	T7 arg7, 
	T8 arg8, 
	T9 arg9, 
	T10 arg10, 
	T11 arg11, 
	T12 arg12, 
	T13 arg13, 
	T14 arg14, 
	T15 arg15, 
	T16 arg16, 
	int count
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<ExtensionAttribute>]
static member InvokeRepeat : 
        action : Action<'T1, 'T2, 'T3, 'T4, 'T5, 'T6, 'T7, 'T8, 'T9, 'T10, 'T11, 'T12, 'T13, 'T14, 'T15, 'T16> * 
        arg1 : 'T1 * 
        arg2 : 'T2 * 
        arg3 : 'T3 * 
        arg4 : 'T4 * 
        arg5 : 'T5 * 
        arg6 : 'T6 * 
        arg7 : 'T7 * 
        arg8 : 'T8 * 
        arg9 : 'T9 * 
        arg10 : 'T10 * 
        arg11 : 'T11 * 
        arg12 : 'T12 * 
        arg13 : 'T13 * 
        arg14 : 'T14 * 
        arg15 : 'T15 * 
        arg16 : 'T16 * 
        count : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>action</dt><dd>Type: System.Action(*T1*, *T2*, *T3*, *T4*, *T5*, *T6*, *T7*, *T8*, *T9*, *T10*, *T11*, *T12*, *T13*, *T14*, *T15*, *T16*)<br />The source Action.</dd><dt>arg1</dt><dd>Type: *T1*<br />The first parameter of the method that the source Action encapsulates.</dd><dt>arg2</dt><dd>Type: *T2*<br />The second parameter of the method that the source Action encapsulates.</dd><dt>arg3</dt><dd>Type: *T3*<br />The third parameter of the method that the source Action encapsulates.</dd><dt>arg4</dt><dd>Type: *T4*<br />The fourth parameter of the method that the source Action encapsulates.</dd><dt>arg5</dt><dd>Type: *T5*<br />The fifth parameter of the method that the source Action encapsulates.</dd><dt>arg6</dt><dd>Type: *T6*<br />The sixth parameter of the method that the source Action encapsulates.</dd><dt>arg7</dt><dd>Type: *T7*<br />The seventh parameter of the method that the source Action encapsulates.</dd><dt>arg8</dt><dd>Type: *T8*<br />The eighth parameter of the method that the source Action encapsulates.</dd><dt>arg9</dt><dd>Type: *T9*<br />The ninth parameter of the method that the source Action encapsulates.</dd><dt>arg10</dt><dd>Type: *T10*<br />The tenth parameter of the method that the source Action encapsulates.</dd><dt>arg11</dt><dd>Type: *T11*<br />The eleventh parameter of the method that the source Action encapsulates.</dd><dt>arg12</dt><dd>Type: *T12*<br />The twelfth parameter of the method that the source Action encapsulates.</dd><dt>arg13</dt><dd>Type: *T13*<br />The thirteenth parameter of the method that the source Action encapsulates.</dd><dt>arg14</dt><dd>Type: *T14*<br />The fourteenth parameter of the method that the source Action encapsulates.</dd><dt>arg15</dt><dd>Type: *T15*<br />The fifteenth parameter of the method that the source Action encapsulates.</dd><dt>arg16</dt><dd>Type: *T16*<br />The sixteenth parameter of the method that the source Action encapsulates.</dd><dt>count</dt><dd>Type: System.Int32<br />The amount of times to invoke the method that the source Action encapsulates.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T1</dt><dd>The type of the first parameter of the method that the source Action encapsulates.</dd><dt>T2</dt><dd>The type of the second parameter of the method that the source Action encapsulates.</dd><dt>T3</dt><dd>The type of the third parameter of the method that the source Action encapsulates.</dd><dt>T4</dt><dd>The type of the fourth parameter of the method that the source Action encapsulates.</dd><dt>T5</dt><dd>The type of the fifth parameter of the method that the source Action encapsulates.</dd><dt>T6</dt><dd>The type of the sixth parameter of the method that the source Action encapsulates.</dd><dt>T7</dt><dd>The type of the seventh parameter of the method that the source Action encapsulates.</dd><dt>T8</dt><dd>The type of the eighth parameter of the method that the source Action encapsulates.</dd><dt>T9</dt><dd>The type of the ninth parameter of the method that the source Action encapsulates.</dd><dt>T10</dt><dd>The type of the tenth parameter of the method that the source Action encapsulates.</dd><dt>T11</dt><dd>The type of the eleventh parameter of the method that the source Action encapsulates.</dd><dt>T12</dt><dd>The type of the twelfth parameter of the method that the source Action encapsulates.</dd><dt>T13</dt><dd>The type of the thirteenth parameter of the method that the source Action encapsulates.</dd><dt>T14</dt><dd>The type of the fourteenth parameter of the method that the source Action encapsulates.</dd><dt>T15</dt><dd>The type of the fifteenth parameter of the method that the source Action encapsulates.</dd><dt>T16</dt><dd>The type of the sixteenth parameter of the method that the source Action encapsulates.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Action(*T1*, *T2*, *T3*, *T4*, *T5*, *T6*, *T7*, *T8*, *T9*, *T10*, *T11*, *T12*, *T13*, *T14*, *T15*, *T16*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>Value greater than zero is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Action_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Action_ArrayExtensions_InvokeRepeat">InvokeRepeat Overload</a><br /><a href="N_DevCase_Core_Extensions_Action">DevCase.Core.Extensions.Action Namespace</a><br />