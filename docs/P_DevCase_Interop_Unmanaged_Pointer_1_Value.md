# Pointer(*T*).Value Property 
 

Gets or sets the value in the pointer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public T this[
	int offset
] { get; set; }
```

**VB**<br />
``` VB
Public Property Value ( 
	offset As Integer
) As T
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As Pointer
Dim offset As Integer
Dim value As T

value = instance.Value(offset)

instance.Value(offset) = value
```

**C++**<br />
``` C++
public:
property T Value[int offset] {
	T get (int offset);
	void set (int offset, T value);
}
```

**F#**<br />
``` F#
member Value : 'T with get, set

```


#### Parameters
&nbsp;<dl><dt>offset</dt><dd>Type: System.Int32<br /></dd></dl>

#### Property Value
Type: <a href="T_DevCase_Interop_Unmanaged_Pointer_1">*T*</a><br />The address offset.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Pointer_1">Pointer(T) Structure</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />