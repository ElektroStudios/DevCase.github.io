# NativeMethods.WriteConsoleOutputAttribute Method 
 

Copies a number of character attributes to consecutive cells of a console screen buffer, beginning at a specified location.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool WriteConsoleOutputAttribute(
	IntPtr consoleOutput,
	CharInfoAttributes[] attributes,
	uint length,
	ConsoleCoordinate writeCoord,
	out uint refNumberOfAttrsWritten
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function WriteConsoleOutputAttribute ( 
	consoleOutput As IntPtr,
	attributes As CharInfoAttributes(),
	length As UInteger,
	writeCoord As ConsoleCoordinate,
	<OutAttribute> ByRef refNumberOfAttrsWritten As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim consoleOutput As IntPtr
Dim attributes As CharInfoAttributes()
Dim length As UInteger
Dim writeCoord As ConsoleCoordinate
Dim refNumberOfAttrsWritten As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.WriteConsoleOutputAttribute(consoleOutput, 
	attributes, length, writeCoord, refNumberOfAttrsWritten)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool WriteConsoleOutputAttribute(
	IntPtr consoleOutput, 
	array<CharInfoAttributes>^ attributes, 
	unsigned int length, 
	ConsoleCoordinate writeCoord, 
	[OutAttribute] unsigned int% refNumberOfAttrsWritten
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member WriteConsoleOutputAttribute : 
        consoleOutput : IntPtr * 
        attributes : CharInfoAttributes[] * 
        length : uint32 * 
        writeCoord : ConsoleCoordinate * 
        refNumberOfAttrsWritten : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>consoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsWrite</a> access right.</dd><dt>attributes</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CharInfoAttributes">DevCase.Interop.Unmanaged.Win32.Enums.CharInfoAttributes</a>[]<br />The attributes to be used when writing to the console screen buffer.</dd><dt>length</dt><dd>Type: System.UInt32<br />The number of screen buffer character cells to which the attributes will be copied.</dd><dt>writeCoord</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleCoordinate</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a> structure that specifies the character coordinates of the first cell in the console screen buffer to which the attributes will be written.</dd><dt>refNumberOfAttrsWritten</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the number of attributes actually written to the console screen buffer.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/writeconsoleoutputattribute" target="_blank">https://docs.microsoft.com/en-us/windows/console/writeconsoleoutputattribute</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />