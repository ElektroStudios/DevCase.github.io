# NativeMethods.ReadConsoleOutput Method 
 

Reads character and color attribute data from a rectangular block of character cells in a console screen buffer, and the function writes the data to a rectangular block at a specified location in the destination buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool ReadConsoleOutput(
	IntPtr consoleOutput,
	IntPtr buffer,
	ConsoleCoordinate bufferSize,
	ConsoleCoordinate bufferCoord,
	ref NativeRectangleSmall refReadRegion
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function ReadConsoleOutput ( 
	consoleOutput As IntPtr,
	buffer As IntPtr,
	bufferSize As ConsoleCoordinate,
	bufferCoord As ConsoleCoordinate,
	ByRef refReadRegion As NativeRectangleSmall
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim consoleOutput As IntPtr
Dim buffer As IntPtr
Dim bufferSize As ConsoleCoordinate
Dim bufferCoord As ConsoleCoordinate
Dim refReadRegion As NativeRectangleSmall
Dim returnValue As Boolean

returnValue = NativeMethods.ReadConsoleOutput(consoleOutput, 
	buffer, bufferSize, bufferCoord, 
	refReadRegion)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool ReadConsoleOutput(
	IntPtr consoleOutput, 
	IntPtr buffer, 
	ConsoleCoordinate bufferSize, 
	ConsoleCoordinate bufferCoord, 
	NativeRectangleSmall% refReadRegion
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member ReadConsoleOutput : 
        consoleOutput : IntPtr * 
        buffer : IntPtr * 
        bufferSize : ConsoleCoordinate * 
        bufferCoord : ConsoleCoordinate * 
        refReadRegion : NativeRectangleSmall byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>consoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsRead</a> (GENERIC_READ) access right.</dd><dt>buffer</dt><dd>Type: System.IntPtr<br />A pointer to a destination buffer that receives the data read from the console screen buffer. 

 This pointer is treated as the origin of a two-dimensional array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_CharInfo">CharInfo</a> structures whose size is specified by the *bufferSize* parameter.</dd><dt>bufferSize</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleCoordinate</a><br />The size of the *buffer* parameter, in character cells. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_X">X</a> member structure is the number of columns; the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_Y">Y</a> member is the number of rows.</dd><dt>bufferCoord</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleCoordinate</a><br />The coordinates of the upper-left cell in the lpBuffer parameter that receives the data read from the console screen buffer. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_X">X</a> member structure is the column; the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_Y">Y</a> member is the row.</dd><dt>refReadRegion</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangleSmall">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangleSmall</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangleSmall">NativeRectangleSmall</a> structure. 

 On input, the structure members specify the upper-left and lower-right coordinates of the console screen buffer rectangle from which the function is to read. 

 On output, the structure members specify the actual rectangle that was used.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/readconsoleoutput" target="_blank">https://docs.microsoft.com/en-us/windows/console/readconsoleoutput</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />