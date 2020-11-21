# VolumeUtil.MaxPathLength Field
 

In `Windows` system, the maximum length for a path is composed of `260` characters. 

 A local path is structured in the following order: drive letter, colon, backslash, name components separated by backslashes, and a terminating null character. 

 For example, the maximum path on drive `C:\` is "`C:\some 256-character path string{NUL}`" where "`{NUL}`" represents the invisible terminating null character for the current system codepage.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const int MaxPathLength = 260
```

**VB**<br />
``` VB
Public Const MaxPathLength As Integer = 260
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = VolumeUtil.MaxPathLength

```

**C++**<br />
``` C++
public:
literal int MaxPathLength = 260
```

**F#**<br />
``` F#
static val mutable MaxPathLength: int
```


#### Field Value
Type: Int32

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/aa365247%28VS.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/aa365247%28VS.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />