# NativeMethods.RtlCrc32 Method 
 

Calculates the CRC-32 checksum for a block of bytes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", SetLastError = true)]
public static uint RtlCrc32(
	byte[] buffer,
	IntPtr size,
	uint initialValue = 4294967295
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", SetLastError := true>]
Public Shared Function RtlCrc32 ( 
	buffer As Byte(),
	size As IntPtr,
	Optional initialValue As UInteger = 4294967295
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim buffer As Byte()
Dim size As IntPtr
Dim initialValue As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.RtlCrc32(buffer, 
	size, initialValue)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", SetLastError = true)]
static unsigned int RtlCrc32(
	[InAttribute] array<unsigned char>^ buffer, 
	[InAttribute] IntPtr size, 
	[InAttribute] unsigned int initialValue = 4294967295
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", SetLastError = true)>]
static member RtlCrc32 : 
        buffer : byte[] * 
        size : IntPtr * 
        ?initialValue : uint32 
(* Defaults:
        let _initialValue = defaultArg initialValue 4294967295
*)
-> uint32 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Byte[]<br />The buffer containing the data to calculate its CRC checksum.</dd><dt>size</dt><dd>Type: System.IntPtr<br />The size of *buffer* parameter, in bytes.</dd><dt>initialValue (Optional)</dt><dd>Type: System.UInt32<br />The value used to initialize the CRC value/register.</dd></dl>

#### Return Value
Type: UInt32<br />Returns the resulting CRC-32 checksum.

## Remarks
<a href="https://processhacker.sourceforge.io/doc/ntrtl_8h.html#a6fbf78a8070e1f0842215d45a89205d5" target="_blank">https://processhacker.sourceforge.io/doc/ntrtl_8h.html#a6fbf78a8070e1f0842215d45a89205d5</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />