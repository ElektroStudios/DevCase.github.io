# SoftwareUtil.Winamp.CurrentVolume Property 
 

Gets or sets the volume level, from 0 to 100, of the current playback in the Winamp process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int CurrentVolume { get; set; }
```

**VB**<br />
``` VB
Public Shared Property CurrentVolume As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = SoftwareUtil.Winamp.CurrentVolume

SoftwareUtil.Winamp.CurrentVolume = value
```

**C++**<br />
``` C++
public:
static property int CurrentVolume {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member CurrentVolume : int with get, set

```


#### Property Value
Type: Int32<br />If Winamp process is running, the return value is the volume level, from 0 to 100, of the current playback in the Winamp process. 

 If Winamp process is not running, the return value is a null reference (`Nothing` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp">SoftwareUtil.Winamp Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />