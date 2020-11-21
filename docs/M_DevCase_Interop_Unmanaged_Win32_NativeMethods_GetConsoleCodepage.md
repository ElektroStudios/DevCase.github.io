# NativeMethods.GetConsoleCodepage Method 
 

Retrieves the input code page used by the console associated with the calling process. 

 A console uses its input code page to translate keyboard input into the corresponding character value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", EntryPoint = "GetConsoleCP", ExactSpelling = true, 
	SetLastError = true)]
public static uint GetConsoleCodepage()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", EntryPoint := "GetConsoleCP", ExactSpelling := true, 
	SetLastError := true>]
Public Shared Function GetConsoleCodepage As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetConsoleCodepage()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", EntryPoint = L"GetConsoleCP", ExactSpelling = true, 
	SetLastError = true)]
static unsigned int GetConsoleCodepage()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", EntryPoint = "GetConsoleCP", ExactSpelling = true, 
	SetLastError = true)>]
static member GetConsoleCodepage : unit -> uint32 

```


#### Return Value
Type: UInt32<br />If the function succeeds, The return value is a code that identifies the code page. 

 If the function fails, the return value is 0. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/getconsolecp" target="_blank">https://docs.microsoft.com/en-us/windows/console/getconsolecp</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />