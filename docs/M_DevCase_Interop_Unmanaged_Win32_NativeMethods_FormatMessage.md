# NativeMethods.FormatMessage Method 
 

Formats a message string. The function requires a message definition as input. The message definition can come from a buffer passed into the function. It can come from a message table resource in an already-loaded module. Or the caller can ask the function to search the system's message table resource(s) for the message definition. The function finds the message definition in a message table resource based on a message identifier and a language identifier. The function copies the formatted message text to an output buffer, processing any embedded insert sequences if requested.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static int FormatMessage(
	FormatMessageFlags flags,
	IntPtr source,
	uint messageId,
	uint languageId,
	ref IntPtr refBuffer,
	uint size,
	string[] arguments
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function FormatMessage ( 
	flags As FormatMessageFlags,
	source As IntPtr,
	messageId As UInteger,
	languageId As UInteger,
	ByRef refBuffer As IntPtr,
	size As UInteger,
	arguments As String()
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim flags As FormatMessageFlags
Dim source As IntPtr
Dim messageId As UInteger
Dim languageId As UInteger
Dim refBuffer As IntPtr
Dim size As UInteger
Dim arguments As String()
Dim returnValue As Integer

returnValue = NativeMethods.FormatMessage(flags, 
	source, messageId, languageId, refBuffer, 
	size, arguments)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static int FormatMessage(
	FormatMessageFlags flags, 
	IntPtr source, 
	unsigned int messageId, 
	unsigned int languageId, 
	IntPtr% refBuffer, 
	unsigned int size, 
	array<String^>^ arguments
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member FormatMessage : 
        flags : FormatMessageFlags * 
        source : IntPtr * 
        messageId : uint32 * 
        languageId : uint32 * 
        refBuffer : IntPtr byref * 
        size : uint32 * 
        arguments : string[] -> int 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FormatMessageFlags">DevCase.Interop.Unmanaged.Win32.Enums.FormatMessageFlags</a><br />The formatting options, and how to interpret the *source* parameter. 

 The low-order byte of *flags* parameter specifies how the function handles line breaks in the output buffer. The low-order byte can also specify the maximum width of a formatted output line.</dd><dt>source</dt><dd>Type: System.IntPtr<br />The location of the message definition. 

 The type of this parameter depends upon the settings in the *flags* parameter.</dd><dt>messageId</dt><dd>Type: System.UInt32<br />The message identifier for the requested message. 

 This parameter is ignored if *flags* includes <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FormatMessageFlags">FromString</a>.</dd><dt>languageId</dt><dd>Type: System.UInt32<br />The language identifier for the requested message. 

 This parameter is ignored if *flags* includes <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FormatMessageFlags">FromString</a>.</dd><dt>refBuffer</dt><dd>Type: System.IntPtr<br />A pointer to a buffer that receives the null-terminated string that specifies the formatted message. 

 If *flags* includes <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FormatMessageFlags">AllocateBuffer</a>, the function allocates a buffer using the LocalAlloc function, and places the pointer to the buffer at the address specified in *refBuffer*. 

 This buffer cannot be larger than 64K bytes.</dd><dt>size</dt><dd>Type: System.UInt32<br />If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FormatMessageFlags">AllocateBuffer</a> flag is not set, this parameter specifies the size of the output buffer. 

 If <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FormatMessageFlags">AllocateBuffer</a> is set, this parameter specifies the minimum number of characters to allocate for an output buffer. 

 Thhe output buffer cannot be larger than 64K bytes.</dd><dt>arguments</dt><dd>Type: System.String[]<br />An array of values that are used as insert values in the formatted message. 

 A %1 in the format string indicates the first value in the Arguments array; a %2 indicates the second argument; and so on. 

 The interpretation of each value depends on the formatting information associated with the insert in the message definition. The default is to treat each value as a pointer to a null-terminated string.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the number of characters stored in the output buffer, excluding the terminating null character. 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-formatmessage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-formatmessage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />