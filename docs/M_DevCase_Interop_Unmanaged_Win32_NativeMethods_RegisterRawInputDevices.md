# NativeMethods.RegisterRawInputDevices Method 
 

Registers the devices that supply the raw input data.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool RegisterRawInputDevices(
	RawInputDevice[] pRawInputDevice,
	uint uiNumDevices,
	uint cbSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function RegisterRawInputDevices ( 
	pRawInputDevice As RawInputDevice(),
	uiNumDevices As UInteger,
	cbSize As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pRawInputDevice As RawInputDevice()
Dim uiNumDevices As UInteger
Dim cbSize As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.RegisterRawInputDevices(pRawInputDevice, 
	uiNumDevices, cbSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool RegisterRawInputDevices(
	array<RawInputDevice>^ pRawInputDevice, 
	unsigned int uiNumDevices, 
	unsigned int cbSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member RegisterRawInputDevices : 
        pRawInputDevice : RawInputDevice[] * 
        uiNumDevices : uint32 * 
        cbSize : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>pRawInputDevice</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">DevCase.Interop.Unmanaged.Win32.Structures.RawInputDevice</a>[]<br />An array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">RawInputDevice</a> structures that represent the devices that supply the raw input.</dd><dt>uiNumDevices</dt><dd>Type: System.UInt32<br />The number of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">RawInputDevice</a> structures pointed to by `pRawInputDevices`.</dd><dt>cbSize</dt><dd>Type: System.UInt32<br />The size, in bytes, of a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputDevice">RawInputDevice</a> structure.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds; `false` (`False` in Visual Basic) otherwise. 

 Call GetLastWin32Error() for more information.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms645600%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms645600%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />