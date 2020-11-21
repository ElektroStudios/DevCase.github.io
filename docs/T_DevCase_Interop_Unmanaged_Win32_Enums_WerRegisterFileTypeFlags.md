# WerRegisterFileTypeFlags Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WerRegisterFile">WerRegisterFile(String, WerRegisterFileType, WerRegisterFileTypeFlags)</a> that can be specified when adding a file to the report.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum WerRegisterFileTypeFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration WerRegisterFileTypeFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As WerRegisterFileTypeFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class WerRegisterFileTypeFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type WerRegisterFileTypeFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerRegisterFileTypeFlags.DeleteWhenDone">**DeleteWhenDone**</td><td>1</td><td>Automatically deletes the file after it is added to the report.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerRegisterFileTypeFlags.AnonymousData">**AnonymousData**</td><td>2</td><td>The file does not contain personal information that could be used to identify or contact the user.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregisterfile" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregisterfile</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />