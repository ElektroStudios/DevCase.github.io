# NativeMethods.RtlCrc64 Method 
 

Calculates the CRC-64 checksum for a block of bytes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", SetLastError = true)]
public static ulong RtlCrc64(
	byte[] buffer,
	IntPtr size,
	ulong initialValue = 18446744073709551615
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", SetLastError := true>]
Public Shared Function RtlCrc64 ( 
	buffer As Byte(),
	size As IntPtr,
	Optional initialValue As ULong = 18446744073709551615
) As ULong
```

**VB Usage**<br />
``` VB Usage
Dim buffer As Byte()
Dim size As IntPtr
Dim initialValue As ULong
Dim returnValue As ULong

returnValue = NativeMethods.RtlCrc64(buffer, 
	size, initialValue)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", SetLastError = true)]
static unsigned long long RtlCrc64(
	[InAttribute] array<unsigned char>^ buffer, 
	[InAttribute] IntPtr size, 
	[InAttribute] unsigned long long initialValue = 18446744073709551615
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", SetLastError = true)>]
static member RtlCrc64 : 
        buffer : byte[] * 
        size : IntPtr * 
        ?initialValue : uint64 
(* Defaults:
        let _initialValue = defaultArg initialValue 18446744073709551615
*)
-> uint64 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Byte[]<br />The buffer containing the data to calculate its CRC checksum.</dd><dt>size</dt><dd>Type: System.IntPtr<br />The size of *buffer* parameter, in bytes.</dd><dt>initialValue (Optional)</dt><dd>Type: System.UInt64<br />The value used to initialize the CRC value/register.</dd></dl>

#### Return Value
Type: UInt64<br />Returns the resulting CRC-64 checksum.

## Remarks
<a href="https://processhacker.sourceforge.io/doc/ntrtl_8h.html#aebf925671290c875f2fd1bf2d4becd58" target="_blank">https://processhacker.sourceforge.io/doc/ntrtl_8h.html#aebf925671290c875f2fd1bf2d4becd58</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />