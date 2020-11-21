# NativeMessage&nbsp;Implicit Conversion (Message to NativeMessage)
 

Performs an implicit conversion from Message to <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator NativeMessage (
	Message msg
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	msg As Message
) As NativeMessage
```

**VB Usage**<br />
``` VB Usage
Dim input As Message
Dim output As NativeMessage

output = CType(input, NativeMessage)
```

**C++**<br />
``` C++
static implicit operator NativeMessage (
	Message msg
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>msg</dt><dd>Type: System.Windows.Forms.Message<br />The Message.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage</a><br />The resulting <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage</a>.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage Structure</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />