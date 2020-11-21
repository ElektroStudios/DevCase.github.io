# VolumeUtil.SupportsEncryption Property (String)
 

Gets a value that determines whether the specified volume supports `Encryption File System` (`EFS`).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool this[
	string rootPathName
] { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property SupportsEncryption ( 
	rootPathName As String
) As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim rootPathName As String
Dim value As Boolean

value = VolumeUtil.SupportsEncryption(rootPathName)

```

**C++**<br />
``` C++
public:
static property bool SupportsEncryption[String^ rootPathName] {
	bool get (String^ rootPathName);
}
```

**F#**<br />
``` F#
static member SupportsEncryption : bool with get

```


#### Parameters
&nbsp;<dl><dt>rootPathName</dt><dd>Type: System.String<br />The root path name (eg. "`C:\`").</dd></dl>

#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the volume supports `Encryption File System` (`EFS`), otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_VolumeUtil_SupportsEncryption">SupportsEncryption Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />