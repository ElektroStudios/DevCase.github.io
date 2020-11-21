# NativeMethods.GetDevicePowerState Method 
 

Retrieves the current power state of the specified device. 

 This function cannot be used to query the power state of a display device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static bool GetDevicePowerState(
	IntPtr hDevice,
	out bool refOn
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function GetDevicePowerState ( 
	hDevice As IntPtr,
	<OutAttribute> ByRef refOn As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDevice As IntPtr
Dim refOn As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.GetDevicePowerState(hDevice, 
	refOn)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static bool GetDevicePowerState(
	[InAttribute] IntPtr hDevice, 
	[OutAttribute] bool% refOn
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetDevicePowerState : 
        hDevice : IntPtr * 
        refOn : bool byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDevice</dt><dd>Type: System.IntPtr<br />A handle to an object on the device, such as a file or socket, or a handle to the device itself.</dd><dt>refOn</dt><dd>Type: System.Boolean<br />A pointer to the variable that receives the power state. 

 This value is `true` (`True` in Visual Basic) if the device is in the working state. Otherwise, it is `false` (`False` in Visual Basic).</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getdevicepowerstate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getdevicepowerstate</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />