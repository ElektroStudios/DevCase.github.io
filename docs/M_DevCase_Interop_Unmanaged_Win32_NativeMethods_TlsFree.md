# NativeMethods.TlsFree Method 
 

Releases a thread local storage (TLS) index, making it available for reuse.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool TlsFree(
	uint tlsIndex
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function TlsFree ( 
	tlsIndex As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim tlsIndex As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.TlsFree(tlsIndex)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool TlsFree(
	unsigned int tlsIndex
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member TlsFree : 
        tlsIndex : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>tlsIndex</dt><dd>Type: System.UInt32<br />The TLS index that was allocated by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_TlsAlloc">TlsAlloc()</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-tlsfree" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-tlsfree</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />