# SoftwareUtil.Winamp.CurrentPlaybackState Property 
 

Gets the current playback state of the Winamp process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SoftwareUtil.Winamp.WinampState CurrentPlaybackState { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentPlaybackState As SoftwareUtil.Winamp.WinampState
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As SoftwareUtil.Winamp.WinampState

value = SoftwareUtil.Winamp.CurrentPlaybackState

```

**C++**<br />
``` C++
public:
static property SoftwareUtil.Winamp.WinampState CurrentPlaybackState {
	SoftwareUtil.Winamp.WinampState get ();
}
```

**F#**<br />
``` F#
static member CurrentPlaybackState : SoftwareUtil.Winamp.WinampState with get

```


#### Property Value
Type: <a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp_WinampState">SoftwareUtil.Winamp.WinampState</a><br />If Winamp process is running, the return value is the current playback state of the Winamp process. 

 If Winamp process is not running, the return value is a null reference (`Nothing` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp">SoftwareUtil.Winamp Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />