# Pointer(*T*).Subtraction Operator 
 

Implements the minus operator.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Pointer<T> operator -(
	Pointer<T> p,
	int value
)
```

**VB**<br />
``` VB
Public Shared Operator - ( 
	p As Pointer(Of T),
	value As Integer
) As Pointer(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim p As Pointer(Of T)
Dim value As Integer
Dim returnValue As Pointer(Of T)

returnValue = (p - value)
```

**C++**<br />
``` C++
public:
static Pointer<T> operator -(
	Pointer<T> p, 
	int value
)
```

**F#**<br />
``` F#
static let inline (-)
        p : Pointer<'T> * 
        value : int  : Pointer<'T>
```


#### Parameters
&nbsp;<dl><dt>p</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Pointer_1">DevCase.Interop.Unmanaged.Pointer</a>(<a href="T_DevCase_Interop_Unmanaged_Pointer_1">*T*</a>)<br />The source Pointer.</dd><dt>value</dt><dd>Type: System.Int32<br />The value to rest.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Pointer_1">Pointer</a>(<a href="T_DevCase_Interop_Unmanaged_Pointer_1">*T*</a>)<br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Pointer_1">Pointer(T) Structure</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />