# CopyFileProgressCallbackReason Enumeration
 

Specifies the reason why <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_CopyProgressRoutine">Delegates.CopyProgressRoutine</a> was called <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CopyFileEx">CopyFileEx(String, String, Delegates.CopyProgressRoutine, IntPtr, Boolean, CopyFileFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum CopyFileProgressCallbackReason
```

**VB**<br />
``` VB
Public Enumeration CopyFileProgressCallbackReason
```

**VB Usage**<br />
``` VB Usage
Dim instance As CopyFileProgressCallbackReason
```

**C++**<br />
``` C++
public enum class CopyFileProgressCallbackReason
```

**F#**<br />
``` F#
type CopyFileProgressCallbackReason
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileProgressCallbackReason.ChunkFinished">**ChunkFinished**</td><td>0</td><td>Another part of the data file was copied.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.CopyFileProgressCallbackReason.StreamSwitch">**StreamSwitch**</td><td>1</td><td>Another stream was created And Is about to be copied. 

 This Is the callback reason given when the callback routine Is first invoked.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa363854(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa363854(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />