# DpiAwareness Enumeration
 

Identifies the dots per inch (dpi) setting for a thread, process, or window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum DpiAwareness
```

**VB**<br />
``` VB
Public Enumeration DpiAwareness
```

**VB Usage**<br />
``` VB Usage
Dim instance As DpiAwareness
```

**C++**<br />
``` C++
public enum class DpiAwareness
```

**F#**<br />
``` F#
type DpiAwareness
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DpiAwareness.Invalid">**Invalid**</td><td>-1</td><td>Invalid DPI awareness. This is an invalid DPI awareness value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DpiAwareness.Unaware">**Unaware**</td><td>0</td><td>DPI unaware. 

 This process does not scale for DPI changes and is always assumed to have a scale factor of 100% (96 DPI). 

 It will be automatically scaled by the system on any other DPI setting.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DpiAwareness.SystemAware">**SystemAware**</td><td>1</td><td>System DPI aware. 

 This process does not scale for DPI changes. 

 It will query for the DPI once and use that value for the lifetime of the process. 

 If the DPI changes, the process will not adjust to the new DPI value. 

 It will be automatically scaled up or down by the system when the DPI changes from the system value..</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DpiAwareness.PerMonitorAware">**PerMonitorAware**</td><td>2</td><td>Per monitor DPI aware. 

 This process checks for the DPI when it is created and adjusts the scale factor whenever the DPI changes. 

 These processes are not automatically scaled by the system.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/windef/ne-windef-dpi_awareness" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/windef/ne-windef-dpi_awareness</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />