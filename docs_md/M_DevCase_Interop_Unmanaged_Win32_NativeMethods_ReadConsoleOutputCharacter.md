# NativeMethods.ReadConsoleOutputCharacter Method 
 

Copies a number of characters from consecutive cells of a console screen buffer, beginning at a specified location.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool ReadConsoleOutputCharacter(
	IntPtr consoleOutput,
	StringBuilder character,
	uint length,
	ConsoleCoordinate readCoord,
	out uint refNumberOfCharsRead
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function ReadConsoleOutputCharacter ( 
	consoleOutput As IntPtr,
	character As StringBuilder,
	length As UInteger,
	readCoord As ConsoleCoordinate,
	<OutAttribute> ByRef refNumberOfCharsRead As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim consoleOutput As IntPtr
Dim character As StringBuilder
Dim length As UInteger
Dim readCoord As ConsoleCoordinate
Dim refNumberOfCharsRead As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.ReadConsoleOutputCharacter(consoleOutput, 
	character, length, readCoord, refNumberOfCharsRead)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool ReadConsoleOutputCharacter(
	IntPtr consoleOutput, 
	StringBuilder^ character, 
	unsigned int length, 
	ConsoleCoordinate readCoord, 
	[OutAttribute] unsigned int% refNumberOfCharsRead
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member ReadConsoleOutputCharacter : 
        consoleOutput : IntPtr * 
        character : StringBuilder * 
        length : uint32 * 
        readCoord : ConsoleCoordinate * 
        refNumberOfCharsRead : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>consoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsRead</a> access right.</dd><dt>character</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives the characters read from the console screen buffer.</dd><dt>length</dt><dd>Type: System.UInt32<br />The number of screen buffer character cells from which to read. 

 The size of the buffer pointed to by the lpCharacter parameter should be `length * sizeof(TCHAR)`.</dd><dt>readCoord</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">DevCase.Interop.Unmanaged.Win32.Structures.ConsoleCoordinate</a><br />The coordinates of the first cell in the console screen buffer from which to read, in characters. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_X">X</a> member is the column, and the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_Y">Y</a> member is the row.</dd><dt>refNumberOfCharsRead</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the number of characters actually read.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/readconsoleoutputcharacter" target="_blank">https://docs.microsoft.com/en-us/windows/console/readconsoleoutputcharacter</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />