# NativeMethods.WideCharToMultiByte Method (UInt32, WideCharConversionType, String, Int32, StringBuilder, Int32, String, Boolean)
 

Maps a UTF-16 (wide character) string to a new character string. The new character string is not necessarily from a multibyte character set. 

 Caution: Using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WideCharToMultiByte">WideCharToMultiByte(CodePage, WideCharConversionType, String, Int32, StringBuilder, Int32, String, Boolean)</a> function incorrectly can compromise the security of your application. Calling this function can easily cause a buffer overrun because the size of the input buffer indicated by *wideCharStr* equals the number of characters in the Unicode string, while the size of the output buffer indicated by *multiByteStr* equals the number of bytes. 

 To avoid a buffer overrun, your application must specify a buffer size appropriate for the data type the buffer receives. 

 Data converted from UTF-16 to non-Unicode encodings is subject to data loss, because a code page might not be able to represent every character used in the specific Unicode data.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static int WideCharToMultiByte(
	uint codePage,
	WideCharConversionType flags,
	string wideCharStr,
	int wideCharStrSize,
	StringBuilder multiByteStr,
	int multiByteStrSize,
	string defaultChar,
	out bool refUsedDefaultChar
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function WideCharToMultiByte ( 
	codePage As UInteger,
	flags As WideCharConversionType,
	wideCharStr As String,
	wideCharStrSize As Integer,
	<OutAttribute> multiByteStr As StringBuilder,
	multiByteStrSize As Integer,
	defaultChar As String,
	<OutAttribute> ByRef refUsedDefaultChar As Boolean
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim codePage As UInteger
Dim flags As WideCharConversionType
Dim wideCharStr As String
Dim wideCharStrSize As Integer
Dim multiByteStr As StringBuilder
Dim multiByteStrSize As Integer
Dim defaultChar As String
Dim refUsedDefaultChar As Boolean
Dim returnValue As Integer

returnValue = NativeMethods.WideCharToMultiByte(codePage, 
	flags, wideCharStr, wideCharStrSize, 
	multiByteStr, multiByteStrSize, 
	defaultChar, refUsedDefaultChar)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static int WideCharToMultiByte(
	unsigned int codePage, 
	WideCharConversionType flags, 
	[InAttribute] String^ wideCharStr, 
	int wideCharStrSize, 
	[OutAttribute] StringBuilder^ multiByteStr, 
	int multiByteStrSize, 
	[InAttribute] String^ defaultChar, 
	[OutAttribute] bool% refUsedDefaultChar
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member WideCharToMultiByte : 
        codePage : uint32 * 
        flags : WideCharConversionType * 
        wideCharStr : string * 
        wideCharStrSize : int * 
        multiByteStr : StringBuilder byref * 
        multiByteStrSize : int * 
        defaultChar : string * 
        refUsedDefaultChar : bool byref -> int 

```


#### Parameters
&nbsp;<dl><dt>codePage</dt><dd>Type: System.UInt32<br />Code page to use in performing the conversion. 

 This parameter can be set to the value of any code page that is installed or available in the operating system.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WideCharConversionType">DevCase.Interop.Unmanaged.Win32.Enums.WideCharConversionType</a><br />Flags indicating the conversion type.</dd><dt>wideCharStr</dt><dd>Type: System.String<br />Pointer to the Unicode string to convert.</dd><dt>wideCharStrSize</dt><dd>Type: System.Int32<br />Size, in characters, of the string indicated by *wideCharStr*. 

 Alternatively, this parameter can be set to -1 if the string is null-terminated. 

 If *wideCharStrSize* is set to 0, the function fails. 

 If this parameter is -1, the function processes the entire input string, including the terminating null character. Therefore, the resulting character string has a terminating null character, and the length returned by the function includes this character. 

 If this parameter is set to a positive integer, the function processes exactly the specified number of characters. 

 If the provided size does not include a terminating null character, the resulting character string is not null-terminated, and the returned length does not include this character.</dd><dt>multiByteStr</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a buffer that receives the converted string.</dd><dt>multiByteStrSize</dt><dd>Type: System.Int32<br />Size, in bytes, of the buffer indicated by *multiByteStr*. 

 If this parameter is set to 0, the function returns the required buffer size for *multiByteStr* and makes no use of the output parameter itself.</dd><dt>defaultChar</dt><dd>Type: System.String<br />Pointer to the character to use if a character cannot be represented in the specified code page. 

 The application sets this parameter to a null reference (`Nothing` in Visual Basic) if the function is to use a system default value. 

 To obtain the system default character, the application can call the `GetCPInfo` or `GetCPInfoEx` function. 

 If you specify the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CodePage">UTF7</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CodePage">UTF8</a> value for *codePage* parameter, this parameter must be set to a null reference (`Nothing` in Visual Basic). Otherwise, the function fails with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_INVALID_PARAMETER</a>.</dd><dt>refUsedDefaultChar</dt><dd>Type: System.Boolean<br />Pointer to a flag that indicates if the function has used a default character in the conversion. 

 The flag is set to `true` (`True` in Visual Basic) if one or more characters in the source string cannot be represented in the specified code page. Otherwise, the flag is set to `false` (`False` in Visual Basic). 

 This parameter can be et to a null reference (`Nothing` in Visual Basic). If you specify the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CodePage">UTF7</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CodePage">UTF8</a> value for *codePage* parameter, this parameter must be set to a null reference (`Nothing` in Visual Basic). Otherwise, the function fails with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_INVALID_PARAMETER</a>.</dd></dl>

#### Return Value
Type: Int32<br />If successful, returns the number of bytes written to the buffer pointed to by *multiByteStr*. 

 If the function succeeds and *multiByteStrSize* is 0, the return value is the required size, in bytes, for the buffer indicated by *multiByteStr*. 

 The function returns 0 (zero) if it does not succeed.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/stringapiset/nf-stringapiset-widechartomultibyte" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/stringapiset/nf-stringapiset-widechartomultibyte</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_WideCharToMultiByte">WideCharToMultiByte Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />