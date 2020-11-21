# NativeMethods.FillConsoleOutputCharacter Method 
 

Writes a character to the console screen buffer a specified number of times, beginning at the specified coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static bool FillConsoleOutputCharacter(
	IntPtr hConsoleOutput,
	char character,
	uint length,
	ConsoleCoordinate writeCoord,
	out uint refNumberOfCharsWritten
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function FillConsoleOutputCharacter ( 
	hConsoleOutput As IntPtr,
	character As Char,
	length As UInteger,
	writeCoord As ConsoleCoordinate,
	<OutAttribute> ByRef refNumberOfCharsWritten As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hConsoleOutput As IntPtr
Dim character As Char
Dim length As UInteger
Dim writeCoord As ConsoleCoordinate
Dim refNumberOfCharsWritten As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.FillConsoleOutputCharacter(hConsoleOutput, 
	character, length, writeCoord, refNumberOfCharsWritten)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static bool FillConsoleOutputCharacter(
	IntPtr hConsoleOutput, 
	wchar_t character, 
	unsigned int length, 
	ConsoleCoordinate writeCoord, 
	[OutAttribute] unsigned int% refNumberOfCharsWritten
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member FillConsoleOutputCharacter : 
        hConsoleOutput : IntPtr * 
        character : char * 
        length : uint32 * 
        writeCoord : ConsoleCoordinate * 
        refNumberOfCharsWritten : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hConsoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsWrite</a> access right.</dd><dt>character</dt><dd>Type: System.Char<br />The character to be written to the console screen buffer.</dd><dt>length</dt><dd>Type: System.UInt32<br />The number of character cells to which the character should be written.</dd><dt>writeCoord</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleCoordinate</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a> structure that specifies the character coordinates of the first cell to which the character is to be written.</dd><dt>refNumberOfCharsWritten</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the number of characters actually written to the console screen buffer.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/fillconsoleoutputcharacter" target="_blank">https://docs.microsoft.com/en-us/windows/console/fillconsoleoutputcharacter</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />