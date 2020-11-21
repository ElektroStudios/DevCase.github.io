# NativeMethods.ILFindLastID Method 
 

Returns a pointer to the last SHITEMID structure in an ITEMIDLIST structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr ILFindLastID(
	IntPtr pidl
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ILFindLastID ( 
	pidl As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim pidl As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.ILFindLastID(pidl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr ILFindLastID(
	IntPtr pidl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)>]
static member ILFindLastID : 
        pidl : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />A pointer to an ITEMIDLIST structure.</dd></dl>

#### Return Value
Type: IntPtr<br />A pointer to the last SHITEMID structure in *pidl*.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilfindlastid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilfindlastid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />