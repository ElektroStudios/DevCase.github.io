# ProfillingUtil.InvokeTimes(*T*) Method (Int32, Func(*T*))
 

Invokes a Func(TResult) for the specified amount of times.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void InvokeTimes<T>(
	int count,
	Func<T> function
)

```

**VB**<br />
``` VB
Public Shared Sub InvokeTimes(Of T) ( 
	count As Integer,
	function As Func(Of T)
)
```

**VB Usage**<br />
``` VB Usage
Dim count As Integer
Dim function As Func(Of T)

ProfillingUtil.InvokeTimes(count, function)
```

**C++**<br />
``` C++
public:
generic<typename T>
static void InvokeTimes(
	int count, 
	Func<T>^ function
)
```

**F#**<br />
``` F#
static member InvokeTimes : 
        count : int * 
        function : Func<'T> -> unit 

```


#### Parameters
&nbsp;<dl><dt>count</dt><dd>Type: System.Int32<br />The amount of times to execute the funtion.</dd><dt>function</dt><dd>Type: System.Func(*T*)<br />The Func(TResult) to be executed.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Diagnostics.Tools.ProfillingUtil.InvokeTimes``1(System.Int32,System.Func{``0})"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_ProfillingUtil">ProfillingUtil Class</a><br /><a href="Overload_DevCase_Core_Diagnostics_Tools_ProfillingUtil_InvokeTimes">InvokeTimes Overload</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />