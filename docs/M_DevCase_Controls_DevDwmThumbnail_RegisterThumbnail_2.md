# DevDwmThumbnail.RegisterThumbnail Method (Nullable(IntPtr))
 

Creates a Desktop Window Manager (DWM) thumbnail that mirrors the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void RegisterThumbnail(
	Nullable<IntPtr> hWnd
)
```

**VB**<br />
``` VB
Public Overridable Sub RegisterThumbnail ( 
	hWnd As Nullable(Of IntPtr)
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevDwmThumbnail
Dim hWnd As Nullable(Of IntPtr)

instance.RegisterThumbnail(hWnd)
```

**C++**<br />
``` C++
public:
virtual void RegisterThumbnail(
	Nullable<IntPtr> hWnd
)
```

**F#**<br />
``` F#
abstract RegisterThumbnail : 
        hWnd : Nullable<IntPtr> -> unit 
override RegisterThumbnail : 
        hWnd : Nullable<IntPtr> -> unit 
```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Nullable(IntPtr)<br />A handle to the window.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevDwmThumbnail">DevDwmThumbnail Class</a><br /><a href="Overload_DevCase_Controls_DevDwmThumbnail_RegisterThumbnail">RegisterThumbnail Overload</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />