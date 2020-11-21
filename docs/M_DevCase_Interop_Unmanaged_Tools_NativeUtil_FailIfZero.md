# NativeUtil.FailIfZero Method (Int32)
 

Evaluates the supplied unmanaged return value and, if it is equal to zero, throws the corresponding Win32Exception. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int FailIfZero(
	int returnValue
)
```

**VB**<br />
``` VB
Public Shared Function FailIfZero ( 
	returnValue As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Integer
Dim returnValue As Integer

returnValue = NativeUtil.FailIfZero(returnValue)
```

**C++**<br />
``` C++
public:
static int FailIfZero(
	int returnValue
)
```

**F#**<br />
``` F#
static member FailIfZero : 
        returnValue : int -> int 

```


#### Parameters
&nbsp;<dl><dt>returnValue</dt><dd>Type: System.Int32<br />The return value to test.</dd></dl>

#### Return Value
Type: Int32<br />The supplied return value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeUtil_FailIfZero">FailIfZero Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />