# NativeMethods.SetStdHandle Method 
 

Sets the handle for the specified standard device (standard input, standard output, or standard error).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetStdHandle(
	StandardDevice std,
	IntPtr handle
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetStdHandle ( 
	std As StandardDevice,
	handle As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim std As StandardDevice
Dim handle As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SetStdHandle(std, 
	handle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetStdHandle(
	StandardDevice std, 
	IntPtr handle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetStdHandle : 
        std : StandardDevice * 
        handle : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>std</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardDevice">DevCase.Interop.Unmanaged.Win32.Enums.StandardDevice</a><br />The standard device for which the handle is to be set.</dd><dt>handle</dt><dd>Type: System.IntPtr<br />The handle for the standard device.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/setstdhandle" target="_blank">https://docs.microsoft.com/en-us/windows/console/setstdhandle</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />