# PssDuplicateFlags Enumeration
 

Duplication flags for use by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PssDuplicateSnapshot">PssDuplicateSnapshot(IntPtr, IntPtr, IntPtr, IntPtr, PssDuplicateFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum PssDuplicateFlags
```

**VB**<br />
``` VB
Public Enumeration PssDuplicateFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As PssDuplicateFlags
```

**C++**<br />
``` C++
public enum class PssDuplicateFlags
```

**F#**<br />
``` F#
type PssDuplicateFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssDuplicateFlags.None">**None**</td><td>0</td><td>No flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PssDuplicateFlags.CloseSource">**CloseSource**</td><td>1</td><td>Free the source handle. 

 This will only succeed if you set the PSS_CREATE_USE_VM_ALLOCATIONS flag when you called PssCaptureSnapshot to create the snapshot and handle. 

 The handle will be freed even if duplication fails. 

 The close operation does not protect against concurrent access to the same descriptor.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/ne-processsnapshot-pss_duplicate_flags" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/ne-processsnapshot-pss_duplicate_flags</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />