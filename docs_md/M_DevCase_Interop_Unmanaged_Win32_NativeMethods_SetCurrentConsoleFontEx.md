# NativeMethods.SetCurrentConsoleFontEx Method 
 

Sets extended information about the current console font.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("kernel32.dll", SetLastError = true)]
public static bool SetCurrentConsoleFontEx(
	IntPtr consoleOutput,
	bool maximumWindow,
	ref ConsoleFontInfoEx refConsoleFontInfoEx
)
```

**VB**<br />
``` VB
<DllImportAttribute("kernel32.dll", SetLastError := true>]
Public Shared Function SetCurrentConsoleFontEx ( 
	consoleOutput As IntPtr,
	maximumWindow As Boolean,
	ByRef refConsoleFontInfoEx As ConsoleFontInfoEx
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim consoleOutput As IntPtr
Dim maximumWindow As Boolean
Dim refConsoleFontInfoEx As ConsoleFontInfoEx
Dim returnValue As Boolean

returnValue = NativeMethods.SetCurrentConsoleFontEx(consoleOutput, 
	maximumWindow, refConsoleFontInfoEx)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"kernel32.dll", SetLastError = true)]
static bool SetCurrentConsoleFontEx(
	IntPtr consoleOutput, 
	bool maximumWindow, 
	ConsoleFontInfoEx% refConsoleFontInfoEx
)
```

**F#**<br />
``` F#
[<DllImportAttribute("kernel32.dll", SetLastError = true)>]
static member SetCurrentConsoleFontEx : 
        consoleOutput : IntPtr * 
        maximumWindow : bool * 
        refConsoleFontInfoEx : ConsoleFontInfoEx byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>consoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. The handle must have the GENERIC_WRITE access right.</dd><dt>maximumWindow</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic), font information is set for the maximum window size. 

 If this parameter is `false` (`False` in Visual Basic), font information is set for the current window size.</dd><dt>refConsoleFontInfoEx</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleFontInfoEx</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx">ConsoleFontInfoEx</a> structure that contains the font information.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/setcurrentconsolefontex" target="_blank">https://docs.microsoft.com/en-us/windows/console/setcurrentconsolefontex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />