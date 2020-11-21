# NativeMethods.GetConsoleDisplayMode Method 
 

Sets the display mode of the specified console screen buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool GetConsoleDisplayMode(
	ref ConsoleDisplayMode refDisplayMode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function GetConsoleDisplayMode ( 
	ByRef refDisplayMode As ConsoleDisplayMode
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refDisplayMode As ConsoleDisplayMode
Dim returnValue As Boolean

returnValue = NativeMethods.GetConsoleDisplayMode(refDisplayMode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool GetConsoleDisplayMode(
	ConsoleDisplayMode% refDisplayMode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member GetConsoleDisplayMode : 
        refDisplayMode : ConsoleDisplayMode byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refDisplayMode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ConsoleDisplayMode">DevCase.Interop.Unmanaged.Win32.Enums.ConsoleDisplayMode</a><br />The display mode of the console.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/getconsoledisplaymode" target="_blank">https://docs.microsoft.com/en-us/windows/console/getconsoledisplaymode</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />