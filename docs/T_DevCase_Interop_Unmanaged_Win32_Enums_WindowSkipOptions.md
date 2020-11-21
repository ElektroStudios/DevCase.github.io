# WindowSkipOptions Enumeration
 

Specifies the child windows to be skipped when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChildWindowFromPointEx">ChildWindowFromPointEx(IntPtr, NativePoint, WindowSkipOptions)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum WindowSkipOptions
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration WindowSkipOptions
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowSkipOptions
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class WindowSkipOptions
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type WindowSkipOptions
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowSkipOptions.None">**None**</td><td>0</td><td>Does not skip any child windows.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowSkipOptions.SkipInvisible">**SkipInvisible**</td><td>1</td><td>Skips invisible child windows.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowSkipOptions.SkipDisabled">**SkipDisabled**</td><td>2</td><td>Skips disabled child windows.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowSkipOptions.SkipTransparent">**SkipTransparent**</td><td>4</td><td>Skips transparent child windows.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb776346(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb776346(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />