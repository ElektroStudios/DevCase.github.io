# TweakingUtil.InstallDate Property 
 

Gets or sets the installation date of the current operating system of this computer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DateTime InstallDate { get; set; }
```

**VB**<br />
``` VB
Public Shared Property InstallDate As DateTime
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As DateTime

value = TweakingUtil.InstallDate

TweakingUtil.InstallDate = value
```

**C++**<br />
``` C++
public:
static property DateTime InstallDate {
	DateTime get ();
	void set (DateTime value);
}
```

**F#**<br />
``` F#
static member InstallDate : DateTime with get, set

```


#### Property Value
Type: DateTime<br />The installation date of the current operating system of this computer.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />