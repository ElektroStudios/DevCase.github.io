# NativeMethods.GetRawInputDeviceList Method (IntPtr, UInt32, UInt32)
 

Enumerates the raw input devices attached to the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static uint GetRawInputDeviceList(
	IntPtr pRawInputDeviceList,
	ref uint refNumDevices,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetRawInputDeviceList ( 
	pRawInputDeviceList As IntPtr,
	ByRef refNumDevices As UInteger,
	size As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim pRawInputDeviceList As IntPtr
Dim refNumDevices As UInteger
Dim size As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetRawInputDeviceList(pRawInputDeviceList, 
	refNumDevices, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static unsigned int GetRawInputDeviceList(
	IntPtr pRawInputDeviceList, 
	unsigned int% refNumDevices, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetRawInputDeviceList : 
        pRawInputDeviceList : IntPtr * 
        refNumDevices : uint32 byref * 
        size : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>pRawInputDeviceList</dt><dd>Type: System.IntPtr<br />An array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDeviceList">RawInputDeviceList</a> structures for the devices attached to the system. 

 If Zero, the number of devices are returned in *refNumDevices* parameter.</dd><dt>refNumDevices</dt><dd>Type: System.UInt32<br />If *pRawInputDeviceList* is Zero, the function populates this variable with the number of devices attached to the system; 

 otherwise, this variable specifies the number of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDeviceList">RawInputDeviceList</a> structures that can be contained in the buffer to which *pRawInputDeviceList* points. 

 If this value is less than the number of devices attached to the system, the function returns the actual number of devices in this variable and fails with `ERROR_INSUFFICIENT_BUFFER`.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size of a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDeviceList">RawInputDeviceList</a> structure, in bytes.</dd></dl>

#### Return Value
Type: UInt32<br />If the function is successful, the return value is the number of devices stored in the buffer pointed to by *pRawInputDeviceList*. 

 On any other error, the function returns `-1` and GetLastWin32Error() returns the error indication.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms645598%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms645598%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetRawInputDeviceList">GetRawInputDeviceList Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />