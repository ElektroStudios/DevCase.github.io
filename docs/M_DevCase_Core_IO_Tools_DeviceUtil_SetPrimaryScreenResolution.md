# DeviceUtil.SetPrimaryScreenResolution Method (Size)
 

Sets the resolution of the primary screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetPrimaryScreenResolution(
	Size size
)
```

**VB**<br />
``` VB
Public Shared Sub SetPrimaryScreenResolution ( 
	size As Size
)
```

**VB Usage**<br />
``` VB Usage
Dim size As SizeDeviceUtil.SetPrimaryScreenResolution(size)
```

**C++**<br />
``` C++
public:
static void SetPrimaryScreenResolution(
	Size size
)
```

**F#**<br />
``` F#
static member SetPrimaryScreenResolution : 
        size : Size -> unit 

```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.Drawing.Size<br />The resolution width and height.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SetPrimaryScreenResolution(New Size(1920, 1080))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DeviceUtil_SetPrimaryScreenResolution">SetPrimaryScreenResolution Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />