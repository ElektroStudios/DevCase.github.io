# NativeUtil.SafePInvoke(*T*) Method (Expression(Func(*T*)), Int32)
 

Invokes a platform invoke encapsulated function, providing a higher safety level for error-handling. 

 If the function that was called using platform invoke has the SetLastError, then it checks the exit code returned by the function, and, if is not same as *successValue*, throws the corresponding Win32Exception.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T SafePInvoke<T>(
	Expression<Func<T>> expr,
	int successValue
)

```

**VB**<br />
``` VB
Public Shared Function SafePInvoke(Of T) ( 
	expr As Expression(Of Func(Of T)),
	successValue As Integer
) As T
```

**VB Usage**<br />
``` VB Usage
Dim expr As Expression(Of Func(Of T))
Dim successValue As Integer
Dim returnValue As T

returnValue = NativeUtil.SafePInvoke(expr, 
	successValue)
```

**C++**<br />
``` C++
public:
generic<typename T>
static T SafePInvoke(
	Expression<Func<T>^>^ expr, 
	int successValue
)
```

**F#**<br />
``` F#
static member SafePInvoke : 
        expr : Expression<Func<'T>> * 
        successValue : int -> 'T 

```


#### Parameters
&nbsp;<dl><dt>expr</dt><dd>Type: System.Linq.Expressions.Expression(Func(*T*))<br />The platform invoke encapsulated function.</dd><dt>successValue</dt><dd>Type: System.Int32<br />\[Missing <param name="successValue"/> documentation for "M:DevCase.Interop.Unmanaged.Tools.NativeUtil.SafePInvoke``1(System.Linq.Expressions.Expression{System.Func{``0}},System.Int32)"\]</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source value type.</dd></dl>

#### Return Value
Type: *T*<br />The type of the return value depends on the function definition.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
<DllImport("User32.dll", SetLastError:=True)>
Public Shared Function GetAsyncKeyState(ByVal vKey As Integer) As Short
End Function

Dim expr As Expression(Of Func(Of Short)) = Function() GetAsyncKeyState(-1) ' -1 is a invalid value.
Dim result As Short = SafePInvoke(Of Short)(expr, successValue:=0)
Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeUtil_SafePInvoke">SafePInvoke Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />