# AudioUtil.SetCurrentApplicationVolume Method (Int32, Int32)
 

Sets the volume of the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetCurrentApplicationVolume(
	int channelLeft,
	int channelRight
)
```

**VB**<br />
``` VB
Public Shared Sub SetCurrentApplicationVolume ( 
	channelLeft As Integer,
	channelRight As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim channelLeft As Integer
Dim channelRight As Integer

AudioUtil.SetCurrentApplicationVolume(channelLeft, 
	channelRight)
```

**C++**<br />
``` C++
public:
static void SetCurrentApplicationVolume(
	int channelLeft, 
	int channelRight
)
```

**F#**<br />
``` F#
static member SetCurrentApplicationVolume : 
        channelLeft : int * 
        channelRight : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>channelLeft</dt><dd>Type: System.Int32<br />The left channel volume, from range 0 to 100.</dd><dt>channelRight</dt><dd>Type: System.Int32<br />The right channel volume, from range 0 to 100.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>channelLeft;A value between 0 and 100 is required. or channelRight;A value between 0 and 100 is required.</td></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Tools_AudioUtil">AudioUtil Class</a><br /><a href="Overload_DevCase_Core_Multimedia_Tools_AudioUtil_SetCurrentApplicationVolume">SetCurrentApplicationVolume Overload</a><br /><a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools Namespace</a><br />