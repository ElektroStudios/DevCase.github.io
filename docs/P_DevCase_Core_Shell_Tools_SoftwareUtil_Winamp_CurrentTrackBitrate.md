# SoftwareUtil.Winamp.CurrentTrackBitrate Property 
 

Gets the bitrate of the current track in the Winamp process. (i.e: 320, 256, 192, 128, etc...)

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int CurrentTrackBitrate { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentTrackBitrate As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = SoftwareUtil.Winamp.CurrentTrackBitrate

```

**C++**<br />
``` C++
public:
static property int CurrentTrackBitrate {
	int get ();
}
```

**F#**<br />
``` F#
static member CurrentTrackBitrate : int with get

```


#### Property Value
Type: Int32<br />If Winamp process is running, the return value is the bitrate of the current track in the Winamp process. 

 If Winamp process is not running, the return value is a null reference (`Nothing` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp">SoftwareUtil.Winamp Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />