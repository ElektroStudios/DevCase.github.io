# NativeMethods.RtlUniform Method 
 

Generates a uniform random number using D.H. Lehmer's 1948 algorithm, between 0 (zero) to UInt32

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll")]
public static uint RtlUniform(
	in uint refSeed
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll">]
Public Shared Function RtlUniform ( 
	ByRef refSeed As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim refSeed As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.RtlUniform(refSeed)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll")]
static unsigned int RtlUniform(
	[InAttribute] unsigned int% refSeed
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll")>]
static member RtlUniform : 
        refSeed : uint32 byref -> uint32 

```


#### Parameters
&nbsp;<dl><dt>refSeed</dt><dd>Type: System.UInt32<br />A number used to calculate a starting value for the random number sequence.</dd></dl>

#### Return Value
Type: UInt32<br />Returns a random number uniformly distributed between 0 (zero) to UInt32.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winternl/nf-winternl-rtluniform" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winternl/nf-winternl-rtluniform</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />