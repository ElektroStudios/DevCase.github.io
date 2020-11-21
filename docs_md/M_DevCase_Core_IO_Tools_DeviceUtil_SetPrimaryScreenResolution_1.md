# DeviceUtil.SetPrimaryScreenResolution Method (Int32, Int32)
 

Sets the resolution of the primary screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetPrimaryScreenResolution(
	int width,
	int height
)
```

**VB**<br />
``` VB
Public Shared Sub SetPrimaryScreenResolution ( 
	width As Integer,
	height As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim width As Integer
Dim height As Integer

DeviceUtil.SetPrimaryScreenResolution(width, 
	height)
```

**C++**<br />
``` C++
public:
static void SetPrimaryScreenResolution(
	int width, 
	int height
)
```

**F#**<br />
``` F#
static member SetPrimaryScreenResolution : 
        width : int * 
        height : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>width</dt><dd>Type: System.Int32<br />The resolution width.</dd><dt>height</dt><dd>Type: System.Int32<br />The resolution height.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SetPrimaryScreenResolution(1920, 1080)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DeviceUtil_SetPrimaryScreenResolution">SetPrimaryScreenResolution Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />