# DevDwmThumbnail.RegisterThumbnail Method (Int32)
 

Creates a Desktop Window Manager (DWM) thumbnail that mirrors the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void RegisterThumbnail(
	int pid
)
```

**VB**<br />
``` VB
Public Overridable Sub RegisterThumbnail ( 
	pid As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevDwmThumbnail
Dim pid As Integer

instance.RegisterThumbnail(pid)
```

**C++**<br />
``` C++
public:
virtual void RegisterThumbnail(
	int pid
)
```

**F#**<br />
``` F#
abstract RegisterThumbnail : 
        pid : int -> unit 
override RegisterThumbnail : 
        pid : int -> unit 
```


#### Parameters
&nbsp;<dl><dt>pid</dt><dd>Type: System.Int32<br />The process identifier that owns the window.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevDwmThumbnail">DevDwmThumbnail Class</a><br /><a href="Overload_DevCase_Controls_DevDwmThumbnail_RegisterThumbnail">RegisterThumbnail Overload</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />