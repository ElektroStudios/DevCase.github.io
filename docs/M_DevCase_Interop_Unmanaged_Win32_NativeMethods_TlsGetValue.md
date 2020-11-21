# NativeMethods.TlsGetValue Method 
 

Retrieves the value in the calling thread's thread local storage (TLS) slot for the specified TLS index. 

 Each thread of a process has its own slot for each TLS index.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr TlsGetValue(
	uint tlsIndex
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function TlsGetValue ( 
	tlsIndex As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim tlsIndex As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.TlsGetValue(tlsIndex)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr TlsGetValue(
	unsigned int tlsIndex
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member TlsGetValue : 
        tlsIndex : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>tlsIndex</dt><dd>Type: System.UInt32<br />The TLS index that was allocated by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_TlsAlloc">TlsAlloc()</a> function.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the value stored in the calling thread's TLS slot associated with the specified index. 

 If *tlsIndex* is a valid index allocated by a successful call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_TlsAlloc">TlsAlloc()</a>, this function always succeeds. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-tlsgetvalue" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-tlsgetvalue</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />