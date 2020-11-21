# VolumeUtil.MaxComponentPathLength Property (String)
 

Gets the maximum path length for a `Unicode` path component for the specified volume. 

 The `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 The maximum extended-length path is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_MaxExtendedPathLength">MaxExtendedPathLength</a> property, read the property description for further details. 

 The extended-length path prefix is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> property, read the property description for further details about its usage.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int this[
	string rootPathName
] { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property MaxComponentPathLength ( 
	rootPathName As String
) As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim rootPathName As String
Dim value As Integer

value = VolumeUtil.MaxComponentPathLength(rootPathName)

```

**C++**<br />
``` C++
public:
static property int MaxComponentPathLength[String^ rootPathName] {
	int get (String^ rootPathName);
}
```

**F#**<br />
``` F#
static member MaxComponentPathLength : int with get

```


#### Parameters
&nbsp;<dl><dt>rootPathName</dt><dd>Type: System.String<br />The root path name (eg. "`C:\`").</dd></dl>

#### Property Value
Type: Int32<br />The maximum path length for a `Unicode` path component for the specified volume, or `-1` in case of the function failed to retrieve the value.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/aa365247%28VS.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/aa365247%28VS.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_VolumeUtil_MaxComponentPathLength">MaxComponentPathLength Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />