# LazyAsync(*T*).IsValueCreated Property 
 

Gets a value that indicates whether a value has been created for this <a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool IsValueCreated { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property IsValueCreated As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As LazyAsync
Dim value As Boolean

value = instance.IsValueCreated

```

**C++**<br />
``` C++
public:
property bool IsValueCreated {
	bool get ();
}
```

**F#**<br />
``` F#
member IsValueCreated : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if a value has been created; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T) Class</a><br /><a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />