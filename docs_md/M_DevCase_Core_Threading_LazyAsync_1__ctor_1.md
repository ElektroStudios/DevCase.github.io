# LazyAsync(*T*) Constructor (Func(*T*), Boolean)
 

Initializes a new instance of the <a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T)</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public LazyAsync(
	Func<T> valueFactory,
	bool isThreadSafe
)
```

**VB**<br />
``` VB
Public Sub New ( 
	valueFactory As Func(Of T),
	isThreadSafe As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim valueFactory As Func(Of T)
Dim isThreadSafe As Boolean

Dim instance As New LazyAsync(valueFactory, 
	isThreadSafe)
```

**C++**<br />
``` C++
public:
LazyAsync(
	Func<T>^ valueFactory, 
	bool isThreadSafe
)
```

**F#**<br />
``` F#
new : 
        valueFactory : Func<'T> * 
        isThreadSafe : bool -> LazyAsync
```


#### Parameters
&nbsp;<dl><dt>valueFactory</dt><dd>Type: System.Func(<a href="T_DevCase_Core_Threading_LazyAsync_1">*T*</a>)<br />The delegate that is invoked to produce the lazily initialized value when it is needed.</dd><dt>isThreadSafe</dt><dd>Type: System.Boolean<br />A value that indicates whether only one thread at time can access to this <a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T)</a>.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T) Class</a><br /><a href="Overload_DevCase_Core_Threading_LazyAsync_1__ctor">LazyAsync(T) Overload</a><br /><a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />