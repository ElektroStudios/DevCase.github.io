# NativeMethods.CoFreeUnusedLibraries Method 
 

Unloads any DLLs that are no longer in use, probably because the DLL no longer has any instantiated COM objects outstanding. 

 Note: This function is provided for compatibility with 16-bit Windows.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll")]
public static void CoFreeUnusedLibraries()
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll">]
Public Shared Sub CoFreeUnusedLibraries
```

**VB Usage**<br />
``` VB Usage

NativeMethods.CoFreeUnusedLibraries()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll")]
static void CoFreeUnusedLibraries()
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll")>]
static member CoFreeUnusedLibraries : unit -> unit 

```


## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-cofreeunusedlibraries" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-cofreeunusedlibraries</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />