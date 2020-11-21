# NativeMethods.MultiByteToWideChar Method (CodePage, MultiByteCharConversionType, String, Int32, StringBuilder, Int32)
 

Maps a character string to a UTF-16 (wide character) string. The character string is not necessarily from a multibyte character set. 

 Caution: Using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar">MultiByteToWideChar(CodePage, MultiByteCharConversionType, Byte[], Int32, Char[], Int32)</a> function incorrectly can compromise the security of your application. 

 Calling this function can easily cause a buffer overrun because the size of the input buffer indicated by *multiByteStr* equals the number of bytes in the string, while the size of the output buffer indicated by *wideCharStr* equals the number of characters. 

 To avoid a buffer overrun, your application must specify a buffer size appropriate for the data type the buffer receives.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static int MultiByteToWideChar(
	CodePage codePage,
	MultiByteCharConversionType flags,
	string multiByteStr,
	int multiByteStrSize,
	StringBuilder wideCharStr,
	int wideCharStrSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function MultiByteToWideChar ( 
	codePage As CodePage,
	flags As MultiByteCharConversionType,
	multiByteStr As String,
	multiByteStrSize As Integer,
	<OutAttribute> wideCharStr As StringBuilder,
	wideCharStrSize As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim codePage As CodePage
Dim flags As MultiByteCharConversionType
Dim multiByteStr As String
Dim multiByteStrSize As Integer
Dim wideCharStr As StringBuilder
Dim wideCharStrSize As Integer
Dim returnValue As Integer

returnValue = NativeMethods.MultiByteToWideChar(codePage, 
	flags, multiByteStr, multiByteStrSize, 
	wideCharStr, wideCharStrSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static int MultiByteToWideChar(
	CodePage codePage, 
	MultiByteCharConversionType flags, 
	[InAttribute] String^ multiByteStr, 
	int multiByteStrSize, 
	[OutAttribute] StringBuilder^ wideCharStr, 
	int wideCharStrSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member MultiByteToWideChar : 
        codePage : CodePage * 
        flags : MultiByteCharConversionType * 
        multiByteStr : string * 
        multiByteStrSize : int * 
        wideCharStr : StringBuilder byref * 
        wideCharStrSize : int -> int 

```


#### Parameters
&nbsp;<dl><dt>codePage</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CodePage">DevCase.Interop.Unmanaged.Win32.Enums.CodePage</a><br />Code page to use in performing the conversion.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MultiByteCharConversionType">DevCase.Interop.Unmanaged.Win32.Enums.MultiByteCharConversionType</a><br />Flags indicating the conversion type.</dd><dt>multiByteStr</dt><dd>Type: System.String<br />Pointer to the character string to convert.</dd><dt>multiByteStrSize</dt><dd>Type: System.Int32<br />Size, in bytes, of the string indicated by the *multiByteStr* parameter. 

 Alternatively, this parameter can be set to -1 if the string is null-terminated. Note that, if *multiByteStrSize* is 0, the function fails. 

 If this parameter is -1, the function processes the entire input string, including the terminating null character. Therefore, the resulting Unicode string has a terminating null character, and the length returned by the function includes this character. 

 If this parameter is set to a positive integer, the function processes exactly the specified number of bytes. If the provided size does not include a terminating null character, the resulting Unicode string is not null-terminated, and the returned length does not include this character.</dd><dt>wideCharStr</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a buffer that receives the converted string.</dd><dt>wideCharStrSize</dt><dd>Type: System.Int32<br />Size, in characters, of the buffer indicated by *wideCharStr*. 

 If this value is 0, the function returns the required buffer size, in characters, including any terminating null character, and makes no use of the *wideCharStr* buffer.</dd></dl>

#### Return Value
Type: Int32<br />Returns the number of characters written to the buffer indicated by *wideCharStr* if successful. 

 If the function succeeds and *wideCharStrSize* is 0, the return value is the required size, in characters, for the buffer indicated by *wideCharStr*. 

 The function returns 0 if it does not succeed.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/stringapiset/nf-stringapiset-multibytetowidechar" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/stringapiset/nf-stringapiset-multibytetowidechar</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MultiByteToWideChar">MultiByteToWideChar Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />