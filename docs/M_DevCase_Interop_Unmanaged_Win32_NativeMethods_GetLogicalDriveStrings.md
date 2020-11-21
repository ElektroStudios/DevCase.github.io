# NativeMethods.GetLogicalDriveStrings Method 
 

Fills a buffer with strings that specify valid drives in the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetLogicalDriveStrings(
	uint bufferLength,
	StringBuilder buffer
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetLogicalDriveStrings ( 
	bufferLength As UInteger,
	buffer As StringBuilder
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim bufferLength As UInteger
Dim buffer As StringBuilder
Dim returnValue As UInteger

returnValue = NativeMethods.GetLogicalDriveStrings(bufferLength, 
	buffer)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetLogicalDriveStrings(
	unsigned int bufferLength, 
	StringBuilder^ buffer
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetLogicalDriveStrings : 
        bufferLength : uint32 * 
        buffer : StringBuilder -> uint32 

```


#### Parameters
&nbsp;<dl><dt>bufferLength</dt><dd>Type: System.UInt32<br />The maximum size of the buffer pointed to by *buffer*, in characters. This size does not include the terminating null character. 

 If this parameter is zero, *buffer* is not used.</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives a series of null-terminated strings, one for each valid drive in the system, plus with an additional null character. 

 Each string is a device name.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the length, in characters, of the strings copied to the buffer, not including the terminating null character. 

 Note that an ANSI-ASCII null character uses one byte, but a Unicode (UTF-16) null character uses two bytes. 

 If the buffer is not large enough, the return value is greater than *bufferLength*. It is the size of the buffer required to hold the drive strings. 

 If the function fails, the return value is zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getlogicaldrivestringsw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getlogicaldrivestringsw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />