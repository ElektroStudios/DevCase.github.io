# NativeMethods.StrFromTimeInterval Method 
 

Converts a time interval, specified in milliseconds, to a string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static int StrFromTimeInterval(
	StringBuilder buffer,
	uint bufferMax,
	uint ms,
	int digits
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function StrFromTimeInterval ( 
	buffer As StringBuilder,
	bufferMax As UInteger,
	ms As UInteger,
	digits As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim bufferMax As UInteger
Dim ms As UInteger
Dim digits As Integer
Dim returnValue As Integer

returnValue = NativeMethods.StrFromTimeInterval(buffer, 
	bufferMax, ms, digits)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static int StrFromTimeInterval(
	StringBuilder^ buffer, 
	unsigned int bufferMax, 
	unsigned int ms, 
	int digits
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member StrFromTimeInterval : 
        buffer : StringBuilder * 
        bufferMax : uint32 * 
        ms : uint32 * 
        digits : int -> int 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that, when this function returns successfully, receives the converted number.</dd><dt>bufferMax</dt><dd>Type: System.UInt32<br />The size of *buffer*, in characters. 

 If *bufferMax* is set to zero, StrFromTimeInterval(StringBuilder, UInt32, UInt32, Int32) will return the minimum size of the character buffer needed to hold the converted string. In this case, *buffer* will not contain the converted string.</dd><dt>ms</dt><dd>Type: System.UInt32<br />The time interval, in milliseconds.</dd><dt>digits</dt><dd>Type: System.Int32<br />The maximum number of significant digits to be represented in *buffer*.</dd></dl>

#### Return Value
Type: Int32<br />Returns the number of characters in *buffer*, excluding the terminating NULL character.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-strfromtimeintervala" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-strfromtimeintervala</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />