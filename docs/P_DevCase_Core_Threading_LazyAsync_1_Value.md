# LazyAsync(*T*).Value Property 
 

Gets the lazily initialized value of the current <a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T)</a>. 

 If the value have not been initialized, blocks the calling thread until the value get initialized. 

 If during initialization an exception have been thrown, it will wrapped into AggregateException and rethrowned on accessing this property.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Threading">DevCase.Core.Threading</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public T Value { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Value As T
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As LazyAsync
Dim value As T

value = instance.Value

```

**C++**<br />
``` C++
public:
property T Value {
	T get ();
}
```

**F#**<br />
``` F#
member Value : 'T with get

```


#### Property Value
Type: <a href="T_DevCase_Core_Threading_LazyAsync_1">*T*</a><br />Tthe lazily initialized value of the current <a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Threading_LazyAsync_1">LazyAsync(T) Class</a><br /><a href="N_DevCase_Core_Threading">DevCase.Core.Threading Namespace</a><br />