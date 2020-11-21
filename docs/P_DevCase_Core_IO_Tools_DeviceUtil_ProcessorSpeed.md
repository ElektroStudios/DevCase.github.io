# DeviceUtil.ProcessorSpeed Property 
 

Gets the current speed of the current CPU, in Mhz.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int ProcessorSpeed { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ProcessorSpeed As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = DeviceUtil.ProcessorSpeed

```

**C++**<br />
``` C++
public:
static property int ProcessorSpeed {
	int get ();
}
```

**F#**<br />
``` F#
static member ProcessorSpeed : int with get

```


#### Property Value
Type: Int32<br />The current speed of the current CPU, in Mhz.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim cpuId As String = ProcessorId()
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />