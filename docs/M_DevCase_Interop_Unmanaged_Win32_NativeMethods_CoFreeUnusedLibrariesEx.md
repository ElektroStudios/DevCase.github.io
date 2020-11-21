# NativeMethods.CoFreeUnusedLibrariesEx Method 
 

Unloads any DLLs that are no longer in use and whose unload delay has expired.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll", SetLastError = true)]
public static void CoFreeUnusedLibrariesEx(
	uint unloadDelay,
	uint reserved = 0
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll", SetLastError := true>]
Public Shared Sub CoFreeUnusedLibrariesEx ( 
	unloadDelay As UInteger,
	Optional reserved As UInteger = 0
)
```

**VB Usage**<br />
``` VB Usage
Dim unloadDelay As UInteger
Dim reserved As UInteger

NativeMethods.CoFreeUnusedLibrariesEx(unloadDelay, 
	reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll", SetLastError = true)]
static void CoFreeUnusedLibrariesEx(
	unsigned int unloadDelay, 
	unsigned int reserved = 0
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll", SetLastError = true)>]
static member CoFreeUnusedLibrariesEx : 
        unloadDelay : uint32 * 
        ?reserved : uint32 
(* Defaults:
        let _reserved = defaultArg reserved 0
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>unloadDelay</dt><dd>Type: System.UInt32<br />The delay in milliseconds between the time that the DLL has stated it can be unloaded until it becomes a candidate to unload. 

 Setting this parameter to INFINITE (-1) uses the system default delay (10 minutes). 

 Setting this parameter to 0 forces the unloading of any DLLs without any delay.</dd><dt>reserved (Optional)</dt><dd>Type: System.UInt32<br />This parameter is reserved and must be 0.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-cofreeunusedlibrariesex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-cofreeunusedlibrariesex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />