# NativeMethods.RestoreLastError Method 
 

Restores the last-error code for the calling thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static void RestoreLastError(
	uint errCode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Sub RestoreLastError ( 
	errCode As UInteger
)
```

**VB Usage**<br />
``` VB Usage
Dim errCode As UInteger

NativeMethods.RestoreLastError(errCode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static void RestoreLastError(
	unsigned int errCode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member RestoreLastError : 
        errCode : uint32 -> unit 

```


#### Parameters
&nbsp;<dl><dt>errCode</dt><dd>Type: System.UInt32<br />The last-error code for the thread.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />