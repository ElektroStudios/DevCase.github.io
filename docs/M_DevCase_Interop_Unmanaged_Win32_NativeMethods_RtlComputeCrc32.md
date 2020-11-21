# NativeMethods.RtlComputeCrc32 Method 
 

Calculate the CRC-32 checksum of a block of bytes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll")]
public static uint RtlComputeCrc32(
	uint initialValue,
	IntPtr buffer,
	uint bufferLen
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll">]
Public Shared Function RtlComputeCrc32 ( 
	initialValue As UInteger,
	buffer As IntPtr,
	bufferLen As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim initialValue As UInteger
Dim buffer As IntPtr
Dim bufferLen As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.RtlComputeCrc32(initialValue, 
	buffer, bufferLen)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll")]
static unsigned int RtlComputeCrc32(
	[InAttribute] unsigned int initialValue, 
	[InAttribute] IntPtr buffer, 
	[InAttribute] unsigned int bufferLen
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll")>]
static member RtlComputeCrc32 : 
        initialValue : uint32 * 
        buffer : IntPtr * 
        bufferLen : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>initialValue</dt><dd>Type: System.UInt32<br />The value used to initialize the CRC value/register.</dd><dt>buffer</dt><dd>Type: System.IntPtr<br />The block of bytes to calculate its CRC-32.</dd><dt>bufferLen</dt><dd>Type: System.UInt32<br />Length of *buffer*, in bytes.</dd></dl>

#### Return Value
Type: UInt32<br />The cumulative CRC-32 checksum of *initialValue* and *bufferLen* bytes of *buffer*.

## Remarks
<a href="https://source.winehq.org/WineAPI/RtlComputeCrc32.html" target="_blank">https://source.winehq.org/WineAPI/RtlComputeCrc32.html</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />