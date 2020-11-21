# VolumeUtil.SupportsExtendedFileAttributes Property 
 

Gets a value that determines whether the current volume supports extended file attributes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SupportsExtendedFileAttributes { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property SupportsExtendedFileAttributes As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = VolumeUtil.SupportsExtendedFileAttributes

```

**C++**<br />
``` C++
public:
static property bool SupportsExtendedFileAttributes {
	bool get ();
}
```

**F#**<br />
``` F#
static member SupportsExtendedFileAttributes : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the volume supports file-based compression, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_VolumeUtil_SupportsExtendedFileAttributes">SupportsExtendedFileAttributes Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />