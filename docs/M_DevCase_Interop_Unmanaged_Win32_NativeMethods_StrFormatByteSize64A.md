# NativeMethods.StrFormatByteSize64A Method 
 

Converts a numeric value into a string that represents the number expressed as a size value in bytes, kilobytes, megabytes, gigabytes, petabytes or exabytes, depending on the size.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr StrFormatByteSize64A(
	ulong number,
	StringBuilder buffer,
	uint bufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function StrFormatByteSize64A ( 
	number As ULong,
	buffer As StringBuilder,
	bufferSize As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim number As ULong
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.StrFormatByteSize64A(number, 
	buffer, bufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr StrFormatByteSize64A(
	unsigned long long number, 
	StringBuilder^ buffer, 
	unsigned int bufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)>]
static member StrFormatByteSize64A : 
        number : uint64 * 
        buffer : StringBuilder * 
        bufferSize : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>number</dt><dd>Type: System.UInt64<br />The numeric value to be converted.</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that, when this function returns successfully, receives the converted number.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of *buffer*, in characters.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns a pointer to the converted string, or NULL if the conversion fails.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-strformatbytesize64a" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-strformatbytesize64a</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />