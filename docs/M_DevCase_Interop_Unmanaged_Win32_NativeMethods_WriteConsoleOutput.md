# NativeMethods.WriteConsoleOutput Method 
 

Writes character and color attribute data to a specified rectangular block of character cells in a console screen buffer. 

 The data to be written is taken from a correspondingly sized rectangular block at a specified location in the source buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static bool WriteConsoleOutput(
	IntPtr consoleOutput,
	IntPtr buffer,
	ConsoleCoordinate bufferSize,
	ConsoleCoordinate bufferCoord,
	ref NativeRectangleSmall refWriteRegion
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function WriteConsoleOutput ( 
	consoleOutput As IntPtr,
	buffer As IntPtr,
	bufferSize As ConsoleCoordinate,
	bufferCoord As ConsoleCoordinate,
	ByRef refWriteRegion As NativeRectangleSmall
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim consoleOutput As IntPtr
Dim buffer As IntPtr
Dim bufferSize As ConsoleCoordinate
Dim bufferCoord As ConsoleCoordinate
Dim refWriteRegion As NativeRectangleSmall
Dim returnValue As Boolean

returnValue = NativeMethods.WriteConsoleOutput(consoleOutput, 
	buffer, bufferSize, bufferCoord, 
	refWriteRegion)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static bool WriteConsoleOutput(
	IntPtr consoleOutput, 
	IntPtr buffer, 
	ConsoleCoordinate bufferSize, 
	ConsoleCoordinate bufferCoord, 
	NativeRectangleSmall% refWriteRegion
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member WriteConsoleOutput : 
        consoleOutput : IntPtr * 
        buffer : IntPtr * 
        bufferSize : ConsoleCoordinate * 
        bufferCoord : ConsoleCoordinate * 
        refWriteRegion : NativeRectangleSmall byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>consoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsWrite</a> access right.</dd><dt>buffer</dt><dd>Type: System.IntPtr<br />The data to be written to the console screen buffer. 

 This pointer is treated as the origin of a two-dimensional array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_CharInfo">CharInfo</a> structures whose size is specified by the *bufferSize* parameter.</dd><dt>bufferSize</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleCoordinate</a><br />The size of the buffer pointed to by the *buffer* parameter, in character cells. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_X">X</a> member is the number of columns; the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_Y">Y</a> member is the number of rows.</dd><dt>bufferCoord</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleCoordinate</a><br />The coordinates of the upper-left cell in the buffer pointed to by the lpBuffer parameter. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_X">X</a> member is the column, and the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_Y">Y</a> member is the row.</dd><dt>refWriteRegion</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangleSmall">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangleSmall</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangleSmall">NativeRectangleSmall</a> structure. 

 On input, the structure members specify the upper-left and lower-right coordinates of the console screen buffer rectangle to write to. 

 On output, the structure members specify the actual rectangle that was used.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/writeconsoleoutput" target="_blank">https://docs.microsoft.com/en-us/windows/console/writeconsoleoutput</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />