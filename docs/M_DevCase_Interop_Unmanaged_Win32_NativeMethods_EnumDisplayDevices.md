# NativeMethods.EnumDisplayDevices Method 
 

Retrieves information about the display devices in the current session.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool EnumDisplayDevices(
	string lpDevice,
	uint iDevNum,
	ref DisplayDevice refDisplayDevice,
	uint flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function EnumDisplayDevices ( 
	lpDevice As String,
	iDevNum As UInteger,
	ByRef refDisplayDevice As DisplayDevice,
	flags As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim lpDevice As String
Dim iDevNum As UInteger
Dim refDisplayDevice As DisplayDevice
Dim flags As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.EnumDisplayDevices(lpDevice, 
	iDevNum, refDisplayDevice, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool EnumDisplayDevices(
	String^ lpDevice, 
	unsigned int iDevNum, 
	DisplayDevice% refDisplayDevice, 
	unsigned int flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member EnumDisplayDevices : 
        lpDevice : string * 
        iDevNum : uint32 * 
        refDisplayDevice : DisplayDevice byref * 
        flags : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>lpDevice</dt><dd>Type: System.String<br />A pointer to the device name. 

 If a null reference (`Nothing` in Visual Basic), the function returns information for the display adapter(s) on the machine, based on *iDevNum*.</dd><dt>iDevNum</dt><dd>Type: System.UInt32<br />An index value that specifies the display device of interest. 

 The operating system identifies each display device in the current session with an index value. 

 The index values are consecutive integers, starting at 0. 

 If the current session has three display devices, for example, they are specified by the index values 0, 1, and 2.</dd><dt>refDisplayDevice</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DisplayDevice">DevCase.Interop.Unmanaged.Win32.Structures.DisplayDevice</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DisplayDevice">DisplayDevice</a> structure that receives information about the display device specified by *iDevNum*. 

 Before calling EnumDisplayDevices(String, UInt32, DisplayDevice, UInt32), you must initialize the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DisplayDevice_SizeOfStruct">SizeOfStruct</a> to the size, in bytes, of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DisplayDevice">DisplayDevice</a>.</dd><dt>flags</dt><dd>Type: System.UInt32<br />Set this flag to `EDD_GET_DEVICE_INTERFACE_NAME` (0x00000001) to retrieve the device interface name for `GUID_DEVINTERFACE_MONITOR`, which is registered by the operating system on a per monitor basis. 

 The value is placed in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DisplayDevice_DeviceID">DeviceID</a> returned in *refDisplayDevice*. 

 The resulting device interface name can be used with `SetupAPI` functions and serves as a link between GDI monitor devices and `SetupAPI` monitor devices.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 The function fails if *iDevNum* is greater than the largest device index.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162609%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162609%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />