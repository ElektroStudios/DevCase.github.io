# UpdateLayeredWindowflags Enumeration
 

For `flags` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateLayeredWindow">UpdateLayeredWindow(IntPtr, IntPtr, NativePoint, NativeSize, IntPtr, NativePoint, Int32, BlendFunction, UpdateLayeredWindowflags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum UpdateLayeredWindowflags
```

**VB**<br />
``` VB
Public Enumeration UpdateLayeredWindowflags
```

**VB Usage**<br />
``` VB Usage
Dim instance As UpdateLayeredWindowflags
```

**C++**<br />
``` C++
public enum class UpdateLayeredWindowflags
```

**F#**<br />
``` F#
type UpdateLayeredWindowflags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.UpdateLayeredWindowflags.ColorKey">**ColorKey**</td><td>1</td><td>Use `pblend` parameter as the blend function. 

 If the display mode is 256 colors or less, the effect of this value is the same as the effect of Opaque.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.UpdateLayeredWindowflags.Alpha">**Alpha**</td><td>2</td><td>Use `crKey` parameter as the transparency color.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.UpdateLayeredWindowflags.Opaque">**Opaque**</td><td>4</td><td>Draw an opaque layered window.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms633556%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms633556%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />