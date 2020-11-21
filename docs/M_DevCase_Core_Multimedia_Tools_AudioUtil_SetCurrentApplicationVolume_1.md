# AudioUtil.SetCurrentApplicationVolume Method (Int32)
 

Sets the volume of the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetCurrentApplicationVolume(
	int volume
)
```

**VB**<br />
``` VB
Public Shared Sub SetCurrentApplicationVolume ( 
	volume As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim volume As Integer

AudioUtil.SetCurrentApplicationVolume(volume)
```

**C++**<br />
``` C++
public:
static void SetCurrentApplicationVolume(
	int volume
)
```

**F#**<br />
``` F#
static member SetCurrentApplicationVolume : 
        volume : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>volume</dt><dd>Type: System.Int32<br />The volume, from range 0 to 100.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>volume,A value between 0 and 100 is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Tools_AudioUtil">AudioUtil Class</a><br /><a href="Overload_DevCase_Core_Multimedia_Tools_AudioUtil_SetCurrentApplicationVolume">SetCurrentApplicationVolume Overload</a><br /><a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools Namespace</a><br />