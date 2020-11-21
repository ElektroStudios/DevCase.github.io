# NativeMethods.GetConsoleOutputCodepage Method 
 

Retrieves the output code page used by the console associated with the calling process. 

 A console uses its output code page to translate the character values written by the various output functions into the images displayed in the console window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", EntryPoint = "GetConsoleOutputCP", 
	ExactSpelling = true, SetLastError = true)]
public static uint GetConsoleOutputCodepage()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", EntryPoint := "GetConsoleOutputCP", 
	ExactSpelling := true, SetLastError := true>]
Public Shared Function GetConsoleOutputCodepage As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetConsoleOutputCodepage()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", EntryPoint = L"GetConsoleOutputCP", 
	ExactSpelling = true, SetLastError = true)]
static unsigned int GetConsoleOutputCodepage()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", EntryPoint = "GetConsoleOutputCP", 
	ExactSpelling = true, SetLastError = true)>]
static member GetConsoleOutputCodepage : unit -> uint32 

```


#### Return Value
Type: UInt32<br />If the function succeeds, the return value is a code that identifies the code page. 

 If the function fails, the return value is 0. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/getconsoleoutputcp" target="_blank">https://docs.microsoft.com/en-us/windows/console/getconsoleoutputcp</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />