# AudioUtil.GetCurrentApplicationVolume Method 
 

Gets the volume of the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static StereoVolume GetCurrentApplicationVolume()
```

**VB**<br />
``` VB
Public Shared Function GetCurrentApplicationVolume As StereoVolume
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As StereoVolume

returnValue = AudioUtil.GetCurrentApplicationVolume()
```

**C++**<br />
``` C++
public:
static StereoVolume GetCurrentApplicationVolume()
```

**F#**<br />
``` F#
static member GetCurrentApplicationVolume : unit -> StereoVolume 

```


#### Return Value
Type: <a href="T_DevCase_Core_Multimedia_StereoVolume">StereoVolume</a><br />A <a href="T_DevCase_Core_Multimedia_StereoVolume">StereoVolume</a> structure that contains the left and right channels volume, from range 0 to 100.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_Tools_AudioUtil">AudioUtil Class</a><br /><a href="N_DevCase_Core_Multimedia_Tools">DevCase.Core.Multimedia.Tools Namespace</a><br />