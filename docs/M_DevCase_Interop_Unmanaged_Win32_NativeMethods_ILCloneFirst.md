# NativeMethods.ILCloneFirst Method 
 

Clones the first SHITEMID structure in an ITEMIDLIST structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)]
public static PIDL ILCloneFirst(
	IntPtr pidl
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ILCloneFirst ( 
	pidl As IntPtr
) As PIDL
```

**VB Usage**<br />
``` VB Usage
Dim pidl As IntPtr
Dim returnValue As PIDL

returnValue = NativeMethods.ILCloneFirst(pidl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true, SetLastError = true)]
static PIDL^ ILCloneFirst(
	IntPtr pidl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)>]
static member ILCloneFirst : 
        pidl : IntPtr -> PIDL 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />A pointer to the ITEMIDLIST structure that you want to clone.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a><br />A pointer to an ITEMIDLIST structure that contains the first SHITEMID structure from the ITEMIDLIST structure specified by *pidl*. 

 Returns NULL on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilclonefirst" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilclonefirst</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />