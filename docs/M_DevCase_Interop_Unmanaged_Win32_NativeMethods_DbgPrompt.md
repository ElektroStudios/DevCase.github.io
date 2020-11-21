# NativeMethods.DbgPrompt Method 
 

Displays a caller-specified user prompt string on the kernel debugger's display device and obtains a user response string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
public static uint DbgPrompt(
	string prompt,
	StringBuilder response,
	uint length
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
Public Shared Function DbgPrompt ( 
	prompt As String,
	response As StringBuilder,
	length As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim prompt As String
Dim response As StringBuilder
Dim length As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.DbgPrompt(prompt, 
	response, length)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
static unsigned int DbgPrompt(
	String^ prompt, 
	StringBuilder^ response, 
	unsigned int length
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
static member DbgPrompt : 
        prompt : string * 
        response : StringBuilder * 
        length : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>prompt</dt><dd>Type: System.String<br />A pointer to a NULL-terminated constant character string that the debugger will display as a user prompt. 

 The maximum size of this string is 512 characters.</dd><dt>response</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a character array buffer that receives the user's response, including a terminating newline character. 

 The maximum size of this buffer is 512 characters.</dd><dt>length</dt><dd>Type: System.UInt32<br />The size, in characters, of the buffer that receives the user's response. 

 This size is the maximum number of characters that the routine will return.</dd></dl>

#### Return Value
Type: UInt32<br />Returns the number of characters that the *response* buffer received, including the terminating newline character. 

 Returns zero if it receives no characters.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/ntddk/nf-ntddk-dbgprompt" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/ntddk/nf-ntddk-dbgprompt</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />