# AudioUtil.SetApplicationVolume Method 
 

Sets the audio volume level for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetApplicationVolume(
	Process pr,
	int volumeLevel
)
```

**VB**<br />
``` VB
Public Shared Sub SetApplicationVolume ( 
	pr As Process,
	volumeLevel As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim pr As Process
Dim volumeLevel As Integer

AudioUtil.SetApplicationVolume(pr, volumeLevel)
```

**C++**<br />
``` C++
public:
static void SetApplicationVolume(
	Process^ pr, 
	int volumeLevel
)
```

**F#**<br />
``` F#
static member SetApplicationVolume : 
        pr : Process * 
        volumeLevel : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>pr</dt><dd>Type: System.Diagnostics.Process<br />The Process.</dd><dt>volumeLevel</dt><dd>Type: System.Int32<br />The new volume level, expressed in the range between 0 and 100.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Tools_AudioUtil">AudioUtil Class</a><br /><a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools Namespace</a><br />