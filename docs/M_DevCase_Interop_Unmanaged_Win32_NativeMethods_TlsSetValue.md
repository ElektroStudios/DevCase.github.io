# NativeMethods.TlsSetValue Method 
 

Stores a value in the calling thread's thread local storage (TLS) slot for the specified TLS index. 

 Each thread of a process has its own slot for each TLS index.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool TlsSetValue(
	uint tlsIndex,
	IntPtr tlsValue
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function TlsSetValue ( 
	tlsIndex As UInteger,
	tlsValue As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim tlsIndex As UInteger
Dim tlsValue As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.TlsSetValue(tlsIndex, 
	tlsValue)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool TlsSetValue(
	unsigned int tlsIndex, 
	[InAttribute] IntPtr tlsValue
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member TlsSetValue : 
        tlsIndex : uint32 * 
        tlsValue : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>tlsIndex</dt><dd>Type: System.UInt32<br />The TLS index that was allocated by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_TlsAlloc">TlsAlloc()</a> function.</dd><dt>tlsValue</dt><dd>Type: System.IntPtr<br />The value to be stored in the calling thread's TLS slot for the index.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-tlssetvalue" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-tlssetvalue</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />