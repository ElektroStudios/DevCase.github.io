# DevDwmThumbnail.RegisterThumbnail Method (Process)
 

Creates a Desktop Window Manager (DWM) thumbnail that mirrors the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void RegisterThumbnail(
	Process process
)
```

**VB**<br />
``` VB
Public Overridable Sub RegisterThumbnail ( 
	process As Process
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevDwmThumbnail
Dim process As Process

instance.RegisterThumbnail(process)
```

**C++**<br />
``` C++
public:
virtual void RegisterThumbnail(
	Process^ process
)
```

**F#**<br />
``` F#
abstract RegisterThumbnail : 
        process : Process -> unit 
override RegisterThumbnail : 
        process : Process -> unit 
```


#### Parameters
&nbsp;<dl><dt>process</dt><dd>Type: System.Diagnostics.Process<br />The Process that owns the window.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevDwmThumbnail">DevDwmThumbnail Class</a><br /><a href="Overload_DevCase_Controls_DevDwmThumbnail_RegisterThumbnail">RegisterThumbnail Overload</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />