# GetRawInputDeviceInfoCommand Enumeration
 

Values for `uiCommand` of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRawInputDeviceInfo">GetRawInputDeviceInfo(IntPtr, GetRawInputDeviceInfoCommand, IntPtr, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum GetRawInputDeviceInfoCommand
```

**VB**<br />
``` VB
Public Enumeration GetRawInputDeviceInfoCommand
```

**VB Usage**<br />
``` VB Usage
Dim instance As GetRawInputDeviceInfoCommand
```

**C++**<br />
``` C++
public enum class GetRawInputDeviceInfoCommand
```

**F#**<br />
``` F#
type GetRawInputDeviceInfoCommand
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetRawInputDeviceInfoCommand.DeviceName">**DeviceName**</td><td>536870919</td><td>`pData` points to a string that contains the device name.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetRawInputDeviceInfoCommand.DeviceInfo">**DeviceInfo**</td><td>536870923</td><td>`pData` points to an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a> structure.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetRawInputDeviceInfoCommand.PreParsedData">**PreParsedData**</td><td>536870917</td><td>`pData` points to the previously parsed data.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms645581%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms645581%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />