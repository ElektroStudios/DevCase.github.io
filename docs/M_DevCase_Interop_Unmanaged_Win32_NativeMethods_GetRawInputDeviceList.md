# NativeMethods.GetRawInputDeviceList Method (RawInputDeviceList[], UInt32, UInt32)
 

Enumerates the raw input devices attached to the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static int GetRawInputDeviceList(
	RawInputDeviceList[] rawInputDeviceList,
	ref uint refNumDevices,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetRawInputDeviceList ( 
	<OutAttribute> rawInputDeviceList As RawInputDeviceList(),
	ByRef refNumDevices As UInteger,
	size As UInteger
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim rawInputDeviceList As RawInputDeviceList()
Dim refNumDevices As UInteger
Dim size As UInteger
Dim returnValue As Integer

returnValue = NativeMethods.GetRawInputDeviceList(rawInputDeviceList, 
	refNumDevices, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static int GetRawInputDeviceList(
	[InAttribute] [OutAttribute] array<RawInputDeviceList>^ rawInputDeviceList, 
	unsigned int% refNumDevices, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetRawInputDeviceList : 
        rawInputDeviceList : RawInputDeviceList[] byref * 
        refNumDevices : uint32 byref * 
        size : uint32 -> int 

```


#### Parameters
&nbsp;<dl><dt>rawInputDeviceList</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDeviceList">DevCase.Interop.Unmanaged.Win32.Structures.RawInputDeviceList</a>[]<br />An array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDeviceList">RawInputDeviceList</a> structures for the devices attached to the system. 

 If NULL, the number of devices are returned in *refNumDevices*.</dd><dt>refNumDevices</dt><dd>Type: System.UInt32<br />If *rawInputDeviceList* is NULL, the function populates this variable with the number of devices attached to the system; otherwise, this variable specifies the number of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDeviceList">RawInputDeviceList</a> structures that can be contained in the buffer to which *rawInputDeviceList* points. 

 If this value is less than the number of devices attached to the system, the function returns the actual number of devices in this variable and fails with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_INSUFFICIENT_BUFFER</a>.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size of a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDeviceList">RawInputDeviceList</a> structure, in bytes.</dd></dl>

#### Return Value
Type: Int32<br />If the function is successful, the return value is the number of devices stored in the buffer pointed to by *rawInputDeviceList*. 

 On any other error, the function returns -1.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getrawinputdevicelist" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getrawinputdevicelist</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRawInputDeviceList">GetRawInputDeviceList Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />