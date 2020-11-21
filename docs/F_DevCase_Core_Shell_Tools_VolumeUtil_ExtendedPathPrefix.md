# VolumeUtil.ExtendedPathPrefix Field
 

In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 To specify an extended-length path, you must use the "`\\?\`" prefix when calling a `Windows API` function, for example: "`\\?\C:\very long path`".

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const string ExtendedPathPrefix = "\\?\"
```

**VB**<br />
``` VB
Public Const ExtendedPathPrefix As String = "\\?\"
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = VolumeUtil.ExtendedPathPrefix

```

**C++**<br />
``` C++
public:
literal String^ ExtendedPathPrefix = "\\?\"
```

**F#**<br />
``` F#
static val mutable ExtendedPathPrefix: string
```


#### Field Value
Type: String

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/aa365247%28VS.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/aa365247%28VS.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />