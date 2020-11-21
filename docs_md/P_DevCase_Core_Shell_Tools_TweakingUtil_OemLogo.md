# TweakingUtil.OemLogo Property 
 

Gets or sets the logo field of the OEM information of this computer. 

 For example: C:\Windows\System32\OEMLogo.bmp

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string OemLogo { get; set; }
```

**VB**<br />
``` VB
Public Shared Property OemLogo As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = TweakingUtil.OemLogo

TweakingUtil.OemLogo = value
```

**C++**<br />
``` C++
public:
static property String^ OemLogo {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
static member OemLogo : string with get, set

```


#### Property Value
Type: String<br />The logo field of the OEM information of this computer.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />