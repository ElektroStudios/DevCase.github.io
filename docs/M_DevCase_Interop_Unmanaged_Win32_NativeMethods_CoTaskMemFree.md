# NativeMethods.CoTaskMemFree Method 
 

Frees a block of task memory previously allocated through a call to the `CoTaskMemAlloc` or `CoTaskMemRealloc` function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll")]
public static void CoTaskMemFree(
	IntPtr pv
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll">]
Public Shared Sub CoTaskMemFree ( 
	pv As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim pv As IntPtrNativeMethods.CoTaskMemFree(pv)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll")]
static void CoTaskMemFree(
	IntPtr pv
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll")>]
static member CoTaskMemFree : 
        pv : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>pv</dt><dd>Type: System.IntPtr<br />A pointer to the memory block to be freed. If this parameter is Zero, the function has no effect.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-cotaskmemfree" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-cotaskmemfree</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />