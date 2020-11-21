# NcRenderingPolicyFlags Enumeration
 

Flags used by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmSetWindowAttribute">DwmSetWindowAttribute(IntPtr, DwmWindowAttribute, IntPtr, UInt32)</a> function to specify the non-client area rendering policy.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum NcRenderingPolicyFlags
```

**VB**<br />
``` VB
Public Enumeration NcRenderingPolicyFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As NcRenderingPolicyFlags
```

**C++**<br />
``` C++
public enum class NcRenderingPolicyFlags
```

**F#**<br />
``` F#
type NcRenderingPolicyFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NcRenderingPolicyFlags.UseWindowStyle">**UseWindowStyle**</td><td>0</td><td>The non-client rendering area is rendered based on the window style.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NcRenderingPolicyFlags.Disabled">**Disabled**</td><td>1</td><td>The non-client area rendering is disabled; the window style is ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NcRenderingPolicyFlags.Enabled">**Enabled**</td><td>2</td><td>The non-client area rendering is enabled; the window style is ignored.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/ne-dwmapi-dwmncrenderingpolicy" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/ne-dwmapi-dwmncrenderingpolicy</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />