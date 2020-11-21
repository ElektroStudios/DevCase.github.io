# AudioUtil.GetApplicationVolume Method 
 

Gets the audio volume level of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int GetApplicationVolume(
	Process pr
)
```

**VB**<br />
``` VB
Public Shared Function GetApplicationVolume ( 
	pr As Process
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim pr As Process
Dim returnValue As Integer

returnValue = AudioUtil.GetApplicationVolume(pr)
```

**C++**<br />
``` C++
public:
static int GetApplicationVolume(
	Process^ pr
)
```

**F#**<br />
``` F#
static member GetApplicationVolume : 
        pr : Process -> int 

```


#### Parameters
&nbsp;<dl><dt>pr</dt><dd>Type: System.Diagnostics.Process<br />The Process.</dd></dl>

#### Return Value
Type: Int32<br />The audio volume, expressed in the range between 0 and 100.

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Tools_AudioUtil">AudioUtil Class</a><br /><a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools Namespace</a><br />