# VolumeUtil.ExtendedUncPathPrefix Field
 

In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 The extended-length path prefix is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> property, read the property description for further details about its usage. 

 The extended-length path prefix can also be used with paths constructed according to the universal naming convention (`UNC`). To specify such a path using `UNC`, you must use the "`\\?\UNC\`" prefix, for example: "`\\?\UNC\server\Very long path`".

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public const string ExtendedUncPathPrefix = "\\?\UNC\"
```

**VB**<br />
``` VB
Public Const ExtendedUncPathPrefix As String = "\\?\UNC\"
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = VolumeUtil.ExtendedUncPathPrefix

```

**C++**<br />
``` C++
public:
literal String^ ExtendedUncPathPrefix = "\\?\UNC\"
```

**F#**<br />
``` F#
static val mutable ExtendedUncPathPrefix: string
```


#### Field Value
Type: String

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/aa365247%28VS.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/aa365247%28VS.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />