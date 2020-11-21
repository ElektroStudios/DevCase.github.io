# BackgroundMode Enumeration
 

The background mode used by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetBkMode">SetBkMode(IntPtr, BackgroundMode)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum BackgroundMode
```

**VB**<br />
``` VB
Public Enumeration BackgroundMode
```

**VB Usage**<br />
``` VB Usage
Dim instance As BackgroundMode
```

**C++**<br />
``` C++
public enum class BackgroundMode
```

**F#**<br />
``` F#
type BackgroundMode
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BackgroundMode.ERROR">**ERROR**</td><td>0</td><td>Indicates that on return, the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetBkMode">SetBkMode(IntPtr, BackgroundMode)</a> has failed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BackgroundMode.TRANSPARENT">**TRANSPARENT**</td><td>1</td><td>Background remains untouched.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.BackgroundMode.OPAQUE">**OPAQUE**</td><td>2</td><td>Background is filled with the current background color before the text, hatched brush, or pen is drawn.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-setbkmode" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-setbkmode</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />