# DeviceUtil.BiosVersion Property 
 

Gets the version of the motherboard BIOS.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string BiosVersion { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property BiosVersion As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = DeviceUtil.BiosVersion

```

**C++**<br />
``` C++
public:
static property String^ BiosVersion {
	String^ get ();
}
```

**F#**<br />
``` F#
static member BiosVersion : string with get

```


#### Property Value
Type: String<br />The version of the motherboard BIOS.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim version As String = BiosVersion()
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />