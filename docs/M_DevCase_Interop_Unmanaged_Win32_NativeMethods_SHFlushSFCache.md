# NativeMethods.SHFlushSFCache Method 
 

Flushes the special folder cache.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true)]
public static void SHFlushSFCache()
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true>]
Public Shared Sub SHFlushSFCache
```

**VB Usage**<br />
``` VB Usage

NativeMethods.SHFlushSFCache()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true)]
static void SHFlushSFCache()
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true)>]
static member SHFlushSFCache : unit -> unit 

```


## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shflushsfcache" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shflushsfcache</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />