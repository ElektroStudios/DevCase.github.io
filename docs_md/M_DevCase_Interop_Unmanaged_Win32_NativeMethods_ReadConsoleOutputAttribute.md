# NativeMethods.ReadConsoleOutputAttribute Method 
 

Copies a specified number of character attributes from consecutive cells of a console screen buffer, beginning at a specified location.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ReadConsoleOutputAttribute(
	IntPtr consoleOutput,
	CharInfoAttributes[] attributes,
	uint length,
	ConsoleCoordinate readCoord,
	out uint refNumberOfAttrsRead
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ReadConsoleOutputAttribute ( 
	consoleOutput As IntPtr,
	attributes As CharInfoAttributes(),
	length As UInteger,
	readCoord As ConsoleCoordinate,
	<OutAttribute> ByRef refNumberOfAttrsRead As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim consoleOutput As IntPtr
Dim attributes As CharInfoAttributes()
Dim length As UInteger
Dim readCoord As ConsoleCoordinate
Dim refNumberOfAttrsRead As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.ReadConsoleOutputAttribute(consoleOutput, 
	attributes, length, readCoord, refNumberOfAttrsRead)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool ReadConsoleOutputAttribute(
	IntPtr consoleOutput, 
	array<CharInfoAttributes>^ attributes, 
	unsigned int length, 
	ConsoleCoordinate readCoord, 
	[OutAttribute] unsigned int% refNumberOfAttrsRead
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member ReadConsoleOutputAttribute : 
        consoleOutput : IntPtr * 
        attributes : CharInfoAttributes[] * 
        length : uint32 * 
        readCoord : ConsoleCoordinate * 
        refNumberOfAttrsRead : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>consoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsRead</a> access right.</dd><dt>attributes</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CharInfoAttributes">DevCase.Interop.Unmanaged.Win32.Enums.CharInfoAttributes</a>[]<br />A pointer to a buffer that receives the attributes being used by the console screen buffer.</dd><dt>length</dt><dd>Type: System.UInt32<br />The number of screen buffer character cells from which to read. 

 The size of the buffer pointed to by the *attributes* parameter should be `length * sizeof(WORD)`.</dd><dt>readCoord</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleCoordinate</a><br />The coordinates of the first cell in the console screen buffer from which to read, in characters. The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_X">X</a> member is the column, and the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_Y">Y</a> member is the row.</dd><dt>refNumberOfAttrsRead</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the number of attributes actually read.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/readconsoleoutputattribute" target="_blank">https://docs.microsoft.com/en-us/windows/console/readconsoleoutputattribute</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />