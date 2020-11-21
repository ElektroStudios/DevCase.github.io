# NativeMethods.GetRegisteredRawInputDevices Method 
 

Retrieves the information about the raw input devices for the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static int GetRegisteredRawInputDevices(
	RawInputDevice[] rawInputDevices,
	ref uint refNumDevices,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetRegisteredRawInputDevices ( 
	<OutAttribute> rawInputDevices As RawInputDevice(),
	ByRef refNumDevices As UInteger,
	size As UInteger
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim rawInputDevices As RawInputDevice()
Dim refNumDevices As UInteger
Dim size As UInteger
Dim returnValue As Integer

returnValue = NativeMethods.GetRegisteredRawInputDevices(rawInputDevices, 
	refNumDevices, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static int GetRegisteredRawInputDevices(
	[InAttribute] [OutAttribute] array<RawInputDevice>^ rawInputDevices, 
	unsigned int% refNumDevices, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetRegisteredRawInputDevices : 
        rawInputDevices : RawInputDevice[] byref * 
        refNumDevices : uint32 byref * 
        size : uint32 -> int 

```


#### Parameters
&nbsp;<dl><dt>rawInputDevices</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">DevCase.Interop.Unmanaged.Win32.Structures.RawInputDevice</a>[]<br />An array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">RawInputDevice</a> structures for the application.</dd><dt>refNumDevices</dt><dd>Type: System.UInt32<br />The number of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">RawInputDevice</a> structures in *pRawInputDevices.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size, in bytes, of a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">RawInputDevice</a> structure.</dd></dl>

#### Return Value
Type: Int32<br />If successful, the function returns a non-negative number that is the number of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">RawInputDevice</a> structures written to the buffer. 

 If the *rawInputDevices* buffer is too small or NULL, the function sets the last error as <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_INSUFFICIENT_BUFFER</a>, returns -1, and sets *refNumDevices* to the required number of devices. 

 If the function fails for any other reason, it returns -1.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getregisteredrawinputdevices" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getregisteredrawinputdevices</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />