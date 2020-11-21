# DeviceUtil.ProcessorId Property 
 

Gets the identifier of the current CPU.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ProcessorId { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ProcessorId As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = DeviceUtil.ProcessorId

```

**C++**<br />
``` C++
public:
static property String^ ProcessorId {
	String^ get ();
}
```

**F#**<br />
``` F#
static member ProcessorId : string with get

```


#### Property Value
Type: String<br />The identifier of the current CPU.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim cpuId As String = ProcessorId()
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />