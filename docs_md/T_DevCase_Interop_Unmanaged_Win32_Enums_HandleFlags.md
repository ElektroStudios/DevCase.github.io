# HandleFlags Enumeration
 

Indicates properties of an object handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum HandleFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration HandleFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As HandleFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class HandleFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type HandleFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HandleFlags.None">**None**</td><td>0</td><td>None.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HandleFlags.Inherit">**Inherit**</td><td>1</td><td>If this flag is set, a child process created with the `inheritHandles` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcess">CreateProcess(String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> set to `true` (`True` in Visual Basic) will inherit the object handle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HandleFlags.ProtectFromClose">**ProtectFromClose**</td><td>2</td><td>If this flag is set, calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CloseHandle">CloseHandle(IntPtr)</a> function will not close the object handle.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/handleapi/nf-handleapi-gethandleinformation" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/handleapi/nf-handleapi-gethandleinformation</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />