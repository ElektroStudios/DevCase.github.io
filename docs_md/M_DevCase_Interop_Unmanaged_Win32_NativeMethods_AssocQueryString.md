# NativeMethods.AssocQueryString Method 
 

Searches for and retrieves a file or protocol association-related string from the registry.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult AssocQueryString(
	AssocF flags,
	AssocStr str,
	string assoc,
	string extra,
	StringBuilder out,
	out uint refOutSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function AssocQueryString ( 
	flags As AssocF,
	str As AssocStr,
	assoc As String,
	extra As String,
	<OutAttribute> out As StringBuilder,
	<OutAttribute> ByRef refOutSize As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim flags As AssocF
Dim str As AssocStr
Dim assoc As String
Dim extra As String
Dim out As StringBuilder
Dim refOutSize As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.AssocQueryString(flags, 
	str, assoc, extra, out, refOutSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult AssocQueryString(
	AssocF flags, 
	AssocStr str, 
	String^ assoc, 
	String^ extra, 
	[OutAttribute] StringBuilder^ out, 
	[InAttribute] [OutAttribute] unsigned int% refOutSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member AssocQueryString : 
        flags : AssocF * 
        str : AssocStr * 
        assoc : string * 
        extra : string * 
        out : StringBuilder byref * 
        refOutSize : uint32 byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_AssocF">DevCase.Interop.Unmanaged.Win32.Enums.AssocF</a><br />The flags that can be used to control the search. 

 It can be any combination of <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_AssocF">AssocF</a> values, except that only one `AssocF.Ini***` value can be included.</dd><dt>str</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_AssocStr">DevCase.Interop.Unmanaged.Win32.Enums.AssocStr</a><br />An <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_AssocStr">AssocStr</a> value that specifies the type of string that is to be returned.</dd><dt>assoc</dt><dd>Type: System.String<br />A pointer to a null-terminated string that is used to determine the root key. 

 The following four types of strings can be used: 

 - A file name extension, such as '.txt'. 

 - A CLSID GUID in the standard '{GUID}' format. 

 - An application's ProgID, such as 'Word.Document.8.' 

 - The name of an application's .exe file (The ASSOCF_OPEN_BYEXENAME flag must be set in flags).</dd><dt>extra</dt><dd>Type: System.String<br />An optional null-terminated string with additional information about the location of the string. 

 It is typically set to a Shell verb such as 'open'. 

 Set this parameter to a null reference (`Nothing` in Visual Basic) if it is not used.</dd><dt>out</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a null-terminated string that, when this function returns successfully, receives the requested string. 

 Set this parameter to a null reference (`Nothing` in Visual Basic) to retrieve the required buffer size.</dd><dt>refOutSize</dt><dd>Type: System.UInt32<br />A pointer to a value that, when calling the function, is set to the number of characters in the *out* buffer. 

 When the function returns successfully, the value is set to the number of characters actually placed in the buffer. 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_AssocF">NoTruncate</a> flag is set in *flags* and the buffer specified in *out* is too small, the function returns `E_POINTER` and the value is set to the required size of the buffer. 

 If *out* is a null reference (`Nothing` in Visual Basic), the function returns `S_FALSE` and *refOutSize* points to the required size, in characters, of the buffer.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns a standard COM error value, including the following: 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>: Success. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_POINTER</a>: The *out* buffer is too small to hold the entire string. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a>: *out* is a null reference (`Nothing` in Visual Basic), *refOutSize* contains the required buffer size.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb773471%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb773471%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />