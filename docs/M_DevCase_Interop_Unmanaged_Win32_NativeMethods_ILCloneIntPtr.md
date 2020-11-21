# NativeMethods.ILCloneIntPtr Method 
 

Clones an ITEMIDLIST structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", EntryPoint = "ILClone", SetLastError = true)]
public static IntPtr ILCloneIntPtr(
	IntPtr pidl
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", EntryPoint := "ILClone", SetLastError := true>]
Public Shared Function ILCloneIntPtr ( 
	pidl As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim pidl As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.ILCloneIntPtr(pidl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", EntryPoint = L"ILClone", SetLastError = true)]
static IntPtr ILCloneIntPtr(
	IntPtr pidl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", EntryPoint = "ILClone", SetLastError = true)>]
static member ILCloneIntPtr : 
        pidl : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />A pointer to the ITEMIDLIST structure to be cloned.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns a pointer to a copy of the ITEMIDLIST structure pointed to by *pidl*.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilclone" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilclone</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />