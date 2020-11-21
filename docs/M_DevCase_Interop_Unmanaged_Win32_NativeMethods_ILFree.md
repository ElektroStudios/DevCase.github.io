# NativeMethods.ILFree Method 
 

Frees an ITEMIDLIST structure allocated by the Shell.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)]
public static void ILFree(
	IntPtr pidl
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Sub ILFree ( 
	pidl As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim pidl As IntPtrNativeMethods.ILFree(pidl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true, SetLastError = true)]
static void ILFree(
	IntPtr pidl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)>]
static member ILFree : 
        pidl : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />A pointer to the ITEMIDLIST structure to be freed. 

 This parameter can be NULL.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilfree" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilfree</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />