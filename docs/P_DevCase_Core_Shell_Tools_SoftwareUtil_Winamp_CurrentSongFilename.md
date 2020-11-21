# SoftwareUtil.Winamp.CurrentSongFilename Property 
 

Gets the filename of the current song that is playing in Winamp process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string CurrentSongFilename { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentSongFilename As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = SoftwareUtil.Winamp.CurrentSongFilename

```

**C++**<br />
``` C++
public:
static property String^ CurrentSongFilename {
	String^ get ();
}
```

**F#**<br />
``` F#
static member CurrentSongFilename : string with get

```


#### Property Value
Type: String<br />If Winamp process is running, the return value is the filename of the current song that is playing. 

 If Winamp process is not running, the return value is a null reference (`Nothing` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp">SoftwareUtil.Winamp Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />