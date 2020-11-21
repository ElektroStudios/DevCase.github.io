# NativeMethods.GetRawInputDeviceInfo Method (IntPtr, UInt32, IntPtr, UInt32)
 

Retrieves information about the raw input device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static int GetRawInputDeviceInfo(
	IntPtr hDevice,
	uint command,
	IntPtr data,
	ref uint refSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetRawInputDeviceInfo ( 
	hDevice As IntPtr,
	command As UInteger,
	data As IntPtr,
	ByRef refSize As UInteger
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hDevice As IntPtr
Dim command As UInteger
Dim data As IntPtr
Dim refSize As UInteger
Dim returnValue As Integer

returnValue = NativeMethods.GetRawInputDeviceInfo(hDevice, 
	command, data, refSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static int GetRawInputDeviceInfo(
	IntPtr hDevice, 
	unsigned int command, 
	IntPtr data, 
	unsigned int% refSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetRawInputDeviceInfo : 
        hDevice : IntPtr * 
        command : uint32 * 
        data : IntPtr * 
        refSize : uint32 byref -> int 

```


#### Parameters
&nbsp;<dl><dt>hDevice</dt><dd>Type: System.IntPtr<br />A handle to the raw input device. 

 This comes from the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_RawInputHeader_Device">Device</a> member or from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRawInputDeviceList">GetRawInputDeviceList(RawInputDeviceList[], UInt32, UInt32)</a>.</dd><dt>command</dt><dd>Type: System.UInt32<br />Specifies what data will be returned in *data*.</dd><dt>data</dt><dd>Type: System.IntPtr<br />A pointer to a buffer that contains the information specified by uiCommand. If *command* is RIDI_DEVICEINFO, set the cbSize member of RID_DEVICE_INFO to `sizeof(RID_DEVICE_INFO)` before calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRawInputDeviceInfo">GetRawInputDeviceInfo(IntPtr, GetRawInputDeviceInfoCommand, IntPtr, UInt32)</a>.</dd><dt>refSize</dt><dd>Type: System.UInt32<br />The size, in bytes, of the data in *data*.</dd></dl>

#### Return Value
Type: Int32<br />If successful, this function returns a non-negative number indicating the number of bytes copied to *data*. 

 If *data* is not large enough for the data, the function returns -1. If *data* is NULL, the function returns a value of zero. 

 In both of these cases, *refSize* is set to the minimum size required for the *data* buffer.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getrawinputdeviceinfoa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getrawinputdeviceinfoa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRawInputDeviceInfo">GetRawInputDeviceInfo Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />