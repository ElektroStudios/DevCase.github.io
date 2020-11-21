# NativeMessage&nbsp;Implicit Conversion (NativeMessage to Message)
 

Performs an implicit conversion from <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage</a> to Message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator Message (
	NativeMessage msg
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	msg As NativeMessage
) As Message
```

**VB Usage**<br />
``` VB Usage
Dim input As NativeMessage
Dim output As Message

output = CType(input, Message)
```

**C++**<br />
``` C++
static implicit operator Message (
	NativeMessage msg
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>msg</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">DevCase.Interop.Unmanaged.Win32.Structures.NativeMessage</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage</a>.</dd></dl>

#### Return Value
Type: Message<br />The resulting Message.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage Structure</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />