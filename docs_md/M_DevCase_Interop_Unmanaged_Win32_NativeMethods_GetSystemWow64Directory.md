# NativeMethods.GetSystemWow64Directory Method 
 

Retrieves the path of the system directory used by WOW64. This directory is not present on 32-bit Windows.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetSystemWow64Directory(
	StringBuilder buffer,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetSystemWow64Directory ( 
	buffer As StringBuilder,
	size As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim size As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetSystemWow64Directory(buffer, 
	size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetSystemWow64Directory(
	StringBuilder^ buffer, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetSystemWow64Directory : 
        buffer : StringBuilder * 
        size : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the buffer to receive the path. This path does not end with a backslash.</dd><dt>size</dt><dd>Type: System.UInt32<br />The maximum size of the buffer, in characers.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the length, in characers, of the string copied to the buffer, not including the terminating null character. 

 If the length is greater than the size of the buffer, the return value is the size of the buffer required to hold the path. 

 If the function fails, the return value is zero. 

 On 32-bit Windows, the function always fails, and the extended error is set to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_CALL_NOT_IMPLEMENTED</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wow64apiset/nf-wow64apiset-getsystemwow64directorya" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wow64apiset/nf-wow64apiset-getsystemwow64directorya</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />