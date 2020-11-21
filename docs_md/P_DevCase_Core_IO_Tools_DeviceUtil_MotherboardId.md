# DeviceUtil.MotherboardId Property 
 

Gets the identifier of the current motherboard.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string MotherboardId { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property MotherboardId As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = DeviceUtil.MotherboardId

```

**C++**<br />
``` C++
public:
static property String^ MotherboardId {
	String^ get ();
}
```

**F#**<br />
``` F#
static member MotherboardId : string with get

```


#### Property Value
Type: String<br />The identifier of the current motherboard.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mbdId As String = MotherboardId()
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />