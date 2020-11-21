# VolumeUtil.MaxExtendedPathLength Field
 

In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 The extended-length path prefix is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> property, read the property description for further details about its usage. 

 Note that the maximum path of `32.767` characters is approximate, because the extended-length path prefix may be expanded to a longer string by the system at run time, and this expansion applies to the total length.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const int MaxExtendedPathLength = 32767
```

**VB**<br />
``` VB
Public Const MaxExtendedPathLength As Integer = 32767
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = VolumeUtil.MaxExtendedPathLength

```

**C++**<br />
``` C++
public:
literal int MaxExtendedPathLength = 32767
```

**F#**<br />
``` F#
static val mutable MaxExtendedPathLength: int
```


#### Field Value
Type: Int32

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/aa365247%28VS.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/aa365247%28VS.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />