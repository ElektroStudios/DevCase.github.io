# FiberFlags Enumeration
 

Flags used by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ConvertThreadToFiberEx">ConvertThreadToFiberEx(IntPtr, FiberFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum FiberFlags
```

**VB**<br />
``` VB
Public Enumeration FiberFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As FiberFlags
```

**C++**<br />
``` C++
public enum class FiberFlags
```

**F#**<br />
``` F#
type FiberFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FiberFlags.None">**None**</td><td>0</td><td>The floating-point state on x86 systems is not switched and data can be corrupted if a fiber uses floating-point arithmetic.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.FiberFlags.FloatSwitch">**FloatSwitch**</td><td>1</td><td>The floating-point state is switched for the fiber.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-convertthreadtofiberex" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-convertthreadtofiberex</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />