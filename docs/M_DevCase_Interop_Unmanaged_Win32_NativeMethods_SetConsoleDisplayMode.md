# NativeMethods.SetConsoleDisplayMode Method 
 

Sets the display mode of the specified console screen buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool SetConsoleDisplayMode(
	IntPtr consoleOutput,
	ConsoleDisplayMode displayMode,
	ref ConsoleCoordinate refNewScreenBufferDimensions
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function SetConsoleDisplayMode ( 
	consoleOutput As IntPtr,
	displayMode As ConsoleDisplayMode,
	ByRef refNewScreenBufferDimensions As ConsoleCoordinate
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim consoleOutput As IntPtr
Dim displayMode As ConsoleDisplayMode
Dim refNewScreenBufferDimensions As ConsoleCoordinate
Dim returnValue As Boolean

returnValue = NativeMethods.SetConsoleDisplayMode(consoleOutput, 
	displayMode, refNewScreenBufferDimensions)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool SetConsoleDisplayMode(
	IntPtr consoleOutput, 
	ConsoleDisplayMode displayMode, 
	ConsoleCoordinate% refNewScreenBufferDimensions
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member SetConsoleDisplayMode : 
        consoleOutput : IntPtr * 
        displayMode : ConsoleDisplayMode * 
        refNewScreenBufferDimensions : ConsoleCoordinate byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>consoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer.</dd><dt>displayMode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ConsoleDisplayMode">DevCase.Interop.Unmanaged.Win32.Enums.ConsoleDisplayMode</a><br />The display mode of the console.</dd><dt>refNewScreenBufferDimensions</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleCoordinate</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a> structure that receives the new dimensions of the screen buffer, in characters.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/setconsoledisplaymode" target="_blank">https://docs.microsoft.com/en-us/windows/console/setconsoledisplaymode</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />