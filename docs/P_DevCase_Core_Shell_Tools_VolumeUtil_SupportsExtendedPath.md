# VolumeUtil.SupportsExtendedPath Property 
 

Gets a value that determines whether the current volume supports usage of Unicode extended-length paths. 

 Read the property description of <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_MaxExtendedPathLength">MaxExtendedPathLength</a> and <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> properties for further details.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SupportsExtendedPath { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property SupportsExtendedPath As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = VolumeUtil.SupportsExtendedPath

```

**C++**<br />
``` C++
public:
static property bool SupportsExtendedPath {
	bool get ();
}
```

**F#**<br />
``` F#
static member SupportsExtendedPath : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the volume supports usage of Unicode extended-length paths, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_VolumeUtil_SupportsExtendedPath">SupportsExtendedPath Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />