# NativeMethods.FillConsoleOutputAttribute Method 
 

Sets the character attributes for a specified number of character cells, beginning at the specified coordinates in a screen buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool FillConsoleOutputAttribute(
	IntPtr hConsoleOutput,
	CharInfoAttributes attribute,
	uint length,
	ConsoleCoordinate writeCoord,
	out uint refNumberOfAttrsWritten
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function FillConsoleOutputAttribute ( 
	hConsoleOutput As IntPtr,
	attribute As CharInfoAttributes,
	length As UInteger,
	writeCoord As ConsoleCoordinate,
	<OutAttribute> ByRef refNumberOfAttrsWritten As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hConsoleOutput As IntPtr
Dim attribute As CharInfoAttributes
Dim length As UInteger
Dim writeCoord As ConsoleCoordinate
Dim refNumberOfAttrsWritten As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.FillConsoleOutputAttribute(hConsoleOutput, 
	attribute, length, writeCoord, refNumberOfAttrsWritten)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool FillConsoleOutputAttribute(
	IntPtr hConsoleOutput, 
	CharInfoAttributes attribute, 
	unsigned int length, 
	ConsoleCoordinate writeCoord, 
	[OutAttribute] unsigned int% refNumberOfAttrsWritten
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member FillConsoleOutputAttribute : 
        hConsoleOutput : IntPtr * 
        attribute : CharInfoAttributes * 
        length : uint32 * 
        writeCoord : ConsoleCoordinate * 
        refNumberOfAttrsWritten : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hConsoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsWrite</a> access right.</dd><dt>attribute</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CharInfoAttributes">DevCase.Interop.Unmanaged.Win32.Enums.CharInfoAttributes</a><br />The attributes to use when writing to the console screen buffer.</dd><dt>length</dt><dd>Type: System.UInt32<br />The number of character cells to be set to the specified color attributes.</dd><dt>writeCoord</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleCoordinate</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a> structure that specifies the character coordinates of the first cell whose attributes are to be set.</dd><dt>refNumberOfAttrsWritten</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the number of character cells whose attributes were actually set.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/fillconsoleoutputattribute" target="_blank">https://docs.microsoft.com/en-us/windows/console/fillconsoleoutputattribute</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />