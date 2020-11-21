# SoftwareUtil.Winamp.CurrentTrackChannels Property 
 

Gets the channel count of the current track in the Winamp process. (i.e: 2, 1)

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int CurrentTrackChannels { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentTrackChannels As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = SoftwareUtil.Winamp.CurrentTrackChannels

```

**C++**<br />
``` C++
public:
static property int CurrentTrackChannels {
	int get ();
}
```

**F#**<br />
``` F#
static member CurrentTrackChannels : int with get

```


#### Property Value
Type: Int32<br />If Winamp process is running, the return value is the channel count of the current track in the Winamp process. 

 If Winamp process is not running, the return value is a null reference (`Nothing` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp">SoftwareUtil.Winamp Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />