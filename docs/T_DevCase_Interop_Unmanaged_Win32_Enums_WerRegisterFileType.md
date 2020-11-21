# WerRegisterFileType Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WerRegisterFile">WerRegisterFile(String, WerRegisterFileType, WerRegisterFileTypeFlags)</a> function that specifies the file type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum WerRegisterFileType
```

**VB**<br />
``` VB
Public Enumeration WerRegisterFileType
```

**VB Usage**<br />
``` VB Usage
Dim instance As WerRegisterFileType
```

**C++**<br />
``` C++
public enum class WerRegisterFileType
```

**F#**<br />
``` F#
type WerRegisterFileType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerRegisterFileType.UserDocument">**UserDocument**</td><td>1</td><td>The document in use by the application at the time of the event. 

 This document is only collected if the Watson server asks for it.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerRegisterFileType.Other">**Other**</td><td>2</td><td>Any other type of file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WerRegisterFileType.Max">**Max**</td><td>3</td><td>The delete when done</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregisterfile" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregisterfile</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />