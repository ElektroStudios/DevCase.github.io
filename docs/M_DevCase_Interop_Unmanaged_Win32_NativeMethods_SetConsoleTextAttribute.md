# NativeMethods.SetConsoleTextAttribute Method 
 

Sets the attributes of characters written to the console screen buffer by the WriteFile or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WriteConsole">WriteConsole(IntPtr, Char[], UInt32, UInt32, IntPtr)</a> function, or echoed by the ReadFile or ReadConsole function. 

 This function affects text written after the function call.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetConsoleTextAttribute(
	IntPtr consoleOutput,
	CharInfoAttributes attributes
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetConsoleTextAttribute ( 
	consoleOutput As IntPtr,
	attributes As CharInfoAttributes
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim consoleOutput As IntPtr
Dim attributes As CharInfoAttributes
Dim returnValue As Boolean

returnValue = NativeMethods.SetConsoleTextAttribute(consoleOutput, 
	attributes)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetConsoleTextAttribute(
	IntPtr consoleOutput, 
	CharInfoAttributes attributes
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetConsoleTextAttribute : 
        consoleOutput : IntPtr * 
        attributes : CharInfoAttributes -> bool 

```


#### Parameters
&nbsp;<dl><dt>consoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsRead</a> access right.</dd><dt>attributes</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CharInfoAttributes">DevCase.Interop.Unmanaged.Win32.Enums.CharInfoAttributes</a><br />The character attributes.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/setconsoletextattribute" target="_blank">https://docs.microsoft.com/en-us/windows/console/setconsoletextattribute</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />