# NativeMethods.GetRawInputDeviceInfo Method (IntPtr, GetRawInputDeviceInfoCommand, IntPtr, UInt32)
 

Retrieves information about the raw input device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static uint GetRawInputDeviceInfo(
	IntPtr hDevice,
	GetRawInputDeviceInfoCommand uiCommand,
	IntPtr pData,
	ref uint refSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetRawInputDeviceInfo ( 
	hDevice As IntPtr,
	uiCommand As GetRawInputDeviceInfoCommand,
	pData As IntPtr,
	ByRef refSize As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hDevice As IntPtr
Dim uiCommand As GetRawInputDeviceInfoCommand
Dim pData As IntPtr
Dim refSize As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetRawInputDeviceInfo(hDevice, 
	uiCommand, pData, refSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static unsigned int GetRawInputDeviceInfo(
	IntPtr hDevice, 
	GetRawInputDeviceInfoCommand uiCommand, 
	IntPtr pData, 
	unsigned int% refSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetRawInputDeviceInfo : 
        hDevice : IntPtr * 
        uiCommand : GetRawInputDeviceInfoCommand * 
        pData : IntPtr * 
        refSize : uint32 byref -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hDevice</dt><dd>Type: System.IntPtr<br />A handle to the raw input device. 

 This comes from the `lParam` in <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Input</a>, from the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputHeader_Device">Device</a> member of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputHeader">RawInputHeader</a> structure, or from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRawInputDeviceList">GetRawInputDeviceList(RawInputDeviceList[], UInt32, UInt32)</a> function. 

 It can also be Zero if an application inserts input data, for example, by using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendInput">SendInput(Int32, Input[], Int32)</a> fcuntion.</dd><dt>uiCommand</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GetRawInputDeviceInfoCommand">DevCase.Interop.Unmanaged.Win32.Enums.GetRawInputDeviceInfoCommand</a><br />Specifies what data will be returned in *pData*.</dd><dt>pData</dt><dd>Type: System.IntPtr<br />A pointer to a buffer that contains the information specified by uiCommand.</dd><dt>refSize</dt><dd>Type: System.UInt32<br />The size, in bytes, of the data in *pData*.</dd></dl>

#### Return Value
Type: UInt32<br />If successful, this function returns a non-negative number indicating the number of bytes copied to *pData*. 

 If *pData* is not large enough for the data, the function returns `-1`. 

 If *pData* is Zero, the function returns `0`. 

 In both of these cases, *refSize* is set to the minimum size required for the *pData* buffer. 

 Call GetLastWin32Error() to identify any other errors.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms645597%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms645597%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRawInputDeviceInfo">GetRawInputDeviceInfo Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />