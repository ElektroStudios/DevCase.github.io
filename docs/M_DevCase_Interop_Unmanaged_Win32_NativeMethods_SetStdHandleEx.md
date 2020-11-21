# NativeMethods.SetStdHandleEx Method 
 

Sets the handle for the specified standard device (standard input, standard output, or standard error) and returns the previous one.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetStdHandleEx(
	StandardDevice std,
	IntPtr handle,
	out IntPtr refPreviousValue
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetStdHandleEx ( 
	std As StandardDevice,
	handle As IntPtr,
	<OutAttribute> ByRef refPreviousValue As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim std As StandardDevice
Dim handle As IntPtr
Dim refPreviousValue As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SetStdHandleEx(std, 
	handle, refPreviousValue)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetStdHandleEx(
	StandardDevice std, 
	IntPtr handle, 
	[OutAttribute] IntPtr% refPreviousValue
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetStdHandleEx : 
        std : StandardDevice * 
        handle : IntPtr * 
        refPreviousValue : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>std</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardDevice">DevCase.Interop.Unmanaged.Win32.Enums.StandardDevice</a><br />The standard device for which the handle is to be set.</dd><dt>handle</dt><dd>Type: System.IntPtr<br />The handle for the standard device.</dd><dt>refPreviousValue</dt><dd>Type: System.IntPtr<br />A pointer to a handle that receives the previous value. 

 Can be Zero, in which case the function behaves exactly as <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetStdHandle">SetStdHandle(StandardDevice, IntPtr)</a>.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="http://undoc.airesoft.co.uk/kernel32.dll/SetStdHandleEx.php" target="_blank">http://undoc.airesoft.co.uk/kernel32.dll/SetStdHandleEx.php</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />