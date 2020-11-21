# NativeMethods.WriteConsole Method 
 

Writes a character string to a console screen buffer beginning at the current cursor location.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static bool WriteConsole(
	IntPtr consoleOutput,
	char[] buffer,
	uint numberOfCharsToWrite,
	out uint refNumberOfCharsWritten,
	IntPtr reserved
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function WriteConsole ( 
	consoleOutput As IntPtr,
	buffer As Char(),
	numberOfCharsToWrite As UInteger,
	<OutAttribute> ByRef refNumberOfCharsWritten As UInteger,
	reserved As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim consoleOutput As IntPtr
Dim buffer As Char()
Dim numberOfCharsToWrite As UInteger
Dim refNumberOfCharsWritten As UInteger
Dim reserved As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.WriteConsole(consoleOutput, 
	buffer, numberOfCharsToWrite, refNumberOfCharsWritten, 
	reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static bool WriteConsole(
	IntPtr consoleOutput, 
	array<wchar_t>^ buffer, 
	unsigned int numberOfCharsToWrite, 
	[OutAttribute] unsigned int% refNumberOfCharsWritten, 
	IntPtr reserved
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member WriteConsole : 
        consoleOutput : IntPtr * 
        buffer : char[] * 
        numberOfCharsToWrite : uint32 * 
        refNumberOfCharsWritten : uint32 byref * 
        reserved : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>consoleOutput</dt><dd>Type: System.IntPtr<br />A handle to the console screen buffer. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsWrite</a> access right.</dd><dt>buffer</dt><dd>Type: System.Char[]<br />A pointer to a buffer that contains characters to be written to the console screen buffer.</dd><dt>numberOfCharsToWrite</dt><dd>Type: System.UInt32<br />The number of characters to be written. 

 If the total size of the specified number of characters exceeds the available heap, the function fails with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_NOT_ENOUGH_MEMORY</a>.</dd><dt>refNumberOfCharsWritten</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the number of characters actually written.</dd><dt>reserved</dt><dd>Type: System.IntPtr<br />Reserved parameter; must be Zero.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/writeconsole" target="_blank">https://docs.microsoft.com/en-us/windows/console/writeconsole</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />