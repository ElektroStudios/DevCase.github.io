# NativeMethods.OleUninitialize Method 
 

Closes the COM library on the apartment, releases any class factories, other COM objects, or servers held by the apartment, disables RPC on the apartment, and frees any resources the apartment maintains.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll", ExactSpelling = true)]
public static void OleUninitialize()
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll", ExactSpelling := true>]
Public Shared Sub OleUninitialize
```

**VB Usage**<br />
``` VB Usage

NativeMethods.OleUninitialize()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll", ExactSpelling = true)]
static void OleUninitialize()
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll", ExactSpelling = true)>]
static member OleUninitialize : unit -> unit 

```


## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/ole2/nf-ole2-oleuninitialize" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/ole2/nf-ole2-oleuninitialize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />