# NativeMethods.StrFormatByteSizeEx Method 
 

Converts a numeric value into a string that represents the number expressed as a size value in bytes, kilobytes, megabytes, gigabytes, petabytes or exabytes, depending on the size. 

 Extends StrFormatByteSizeW by offering the option to round to the nearest displayed digit or to discard undisplayed digits.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Unicode, ExactSpelling = true)]
public static HResult StrFormatByteSizeEx(
	ulong number,
	StrFormatByteSizeFlags flags,
	StringBuilder buffer,
	uint bufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Unicode, ExactSpelling := true>]
Public Shared Function StrFormatByteSizeEx ( 
	number As ULong,
	flags As StrFormatByteSizeFlags,
	buffer As StringBuilder,
	bufferSize As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim number As ULong
Dim flags As StrFormatByteSizeFlags
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.StrFormatByteSizeEx(number, 
	flags, buffer, bufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Unicode, ExactSpelling = true)]
static HResult StrFormatByteSizeEx(
	unsigned long long number, 
	StrFormatByteSizeFlags flags, 
	StringBuilder^ buffer, 
	unsigned int bufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Unicode, ExactSpelling = true)>]
static member StrFormatByteSizeEx : 
        number : uint64 * 
        flags : StrFormatByteSizeFlags * 
        buffer : StringBuilder * 
        bufferSize : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>number</dt><dd>Type: System.UInt64<br />The numeric value to be converted.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StrFormatByteSizeFlags">DevCase.Interop.Unmanaged.Win32.Enums.StrFormatByteSizeFlags</a><br />Specifies whether to round or truncate undisplayed digits.</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that, when this function returns successfully, receives the converted number.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of *buffer*, in characters.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-strformatbytesizeex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-strformatbytesizeex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />