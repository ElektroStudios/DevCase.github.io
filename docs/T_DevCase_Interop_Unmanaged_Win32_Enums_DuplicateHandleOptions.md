# DuplicateHandleOptions Enumeration
 

Specifies optional actions for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DuplicateHandle">DuplicateHandle(IntPtr, IntPtr, IntPtr, IntPtr, GenericAccessRights, Boolean, DuplicateHandleOptions)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum DuplicateHandleOptions
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration DuplicateHandleOptions
```

**VB Usage**<br />
``` VB Usage
Dim instance As DuplicateHandleOptions
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class DuplicateHandleOptions
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type DuplicateHandleOptions
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DuplicateHandleOptions.CloseSourceHandle">**CloseSourceHandle**</td><td>1</td><td>Closes the source handle. This occurs regardless of any error status returned.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DuplicateHandleOptions.SameAccess">**SameAccess**</td><td>2</td><td>Ignores the dwDesiredAccess parameter. The duplicate handle has the same access as the source handle.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms724251(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms724251(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />