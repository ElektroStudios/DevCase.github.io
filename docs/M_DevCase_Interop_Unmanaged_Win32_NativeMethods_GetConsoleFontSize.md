# NativeMethods.GetConsoleFontSize Method 
 

Retrieves the size of the font used by the specified console screen buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("kernel32.dll", SetLastError = true)]
public static ConsoleCoordinate GetConsoleFontSize(
	IntPtr consoleOutput,
	int fontIndex
)
```

**VB**<br />
``` VB
<DllImportAttribute("kernel32.dll", SetLastError := true>]
Public Shared Function GetConsoleFontSize ( 
	consoleOutput As IntPtr,
	fontIndex As Integer
) As ConsoleCoordinate
```

**VB Usage**<br />
``` VB Usage
Dim consoleOutput As IntPtr
Dim fontIndex As Integer
Dim returnValue As ConsoleCoordinate

returnValue = NativeMethods.GetConsoleFontSize(consoleOutput, 
	fontIndex)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"kernel32.dll", SetLastError = true)]
static ConsoleCoordinate GetConsoleFontSize(
	IntPtr consoleOutput, 
	int fontIndex
)
```

**F#**<br />
``` F#
[<DllImportAttribute("kernel32.dll", SetLastError = true)>]
static member GetConsoleFontSize : 
        consoleOutput : IntPtr * 
        fontIndex : int -> ConsoleCoordinate 

```


#### Parameters
&nbsp;<dl><dt>consoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. The handle must have the GENERIC_READ access right.</dd><dt>fontIndex</dt><dd>Type: System.Int32<br />The index of the font whose size is to be retrieved. 

 This index is obtained by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetCurrentConsoleFont">GetCurrentConsoleFont(IntPtr, Boolean, ConsoleFontInfo)</a> function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a><br />If the function succeeds, the return value is a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a> structure that contains the width and height of each character in the font, in logical units. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_X">X</a> member contains the width, while the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_Y">Y</a> member contains the height. 

 If the function fails, the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_X">X</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_Y">Y</a> members are zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/getconsolefontsize" target="_blank">https://docs.microsoft.com/en-us/windows/console/getconsolefontsize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />