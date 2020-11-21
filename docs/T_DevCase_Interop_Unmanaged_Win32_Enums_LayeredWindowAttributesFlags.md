# LayeredWindowAttributesFlags Enumeration
 

An action to be taken. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetLayeredWindowAttributes">GetLayeredWindowAttributes(IntPtr, UInt32, Int32, LayeredWindowAttributesFlags)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetLayeredWindowAttributes">SetLayeredWindowAttributes(IntPtr, UInt32, Int32, LayeredWindowAttributesFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum LayeredWindowAttributesFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration LayeredWindowAttributesFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As LayeredWindowAttributesFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class LayeredWindowAttributesFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type LayeredWindowAttributesFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LayeredWindowAttributesFlags.ColorKey">**ColorKey**</td><td>1</td><td>Uses `crKey` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetLayeredWindowAttributes">SetLayeredWindowAttributes(IntPtr, UInt32, Int32, LayeredWindowAttributesFlags)</a> function to set the transparency color.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LayeredWindowAttributesFlags.Alpha">**Alpha**</td><td>2</td><td>Uses `bAlpha` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetLayeredWindowAttributes">SetLayeredWindowAttributes(IntPtr, UInt32, Int32, LayeredWindowAttributesFlags)</a> function to determine the opacity of the layered window.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633540%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633540%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />