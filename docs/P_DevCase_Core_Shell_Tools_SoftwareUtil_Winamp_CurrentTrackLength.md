# SoftwareUtil.Winamp.CurrentTrackLength Property 
 

Gets the length, in milliseconds, of the current track in the Winamp process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int CurrentTrackLength { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentTrackLength As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = SoftwareUtil.Winamp.CurrentTrackLength

```

**C++**<br />
``` C++
public:
static property int CurrentTrackLength {
	int get ();
}
```

**F#**<br />
``` F#
static member CurrentTrackLength : int with get

```


#### Property Value
Type: Int32<br />If Winamp process is running, the length, in milliseconds, of the current track in the Winamp process. 

 If Winamp process is not running, the return value is a null reference (`Nothing` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp">SoftwareUtil.Winamp Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />