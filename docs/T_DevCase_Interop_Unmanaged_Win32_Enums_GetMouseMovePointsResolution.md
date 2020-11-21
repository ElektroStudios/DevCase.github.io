# GetMouseMovePointsResolution Enumeration
 

Indicate how to retrieve mouse poitns when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMouseMovePointsEx">GetMouseMovePointsEx(UInt32, MouseMovePoint, MouseMovePoint[], Int32, GetMouseMovePointsResolution)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum GetMouseMovePointsResolution
```

**VB**<br />
``` VB
Public Enumeration GetMouseMovePointsResolution
```

**VB Usage**<br />
``` VB Usage
Dim instance As GetMouseMovePointsResolution
```

**C++**<br />
``` C++
public enum class GetMouseMovePointsResolution
```

**F#**<br />
``` F#
type GetMouseMovePointsResolution
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetMouseMovePointsResolution.UseDisplayPoints">**UseDisplayPoints**</td><td>1</td><td>Retrieves the points using the display resolution.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetMouseMovePointsResolution.UseHighResolutionPoints">**UseHighResolutionPoints**</td><td>2</td><td>Retrieves high resolution points. 

 Points can range from zero to 65,535 (0xFFFF) in both x- and y-coordinates. 

 This is the resolution provided by absolute coordinate pointing devices such as drawing tablets.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getmousemovepointsex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getmousemovepointsex</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />