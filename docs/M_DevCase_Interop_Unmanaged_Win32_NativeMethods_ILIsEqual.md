# NativeMethods.ILIsEqual Method 
 

Tests whether two ITEMIDLIST structures are equal in a binary comparison.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ILIsEqual(
	IntPtr pidl1,
	IntPtr pidl2
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ILIsEqual ( 
	pidl1 As IntPtr,
	pidl2 As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pidl1 As IntPtr
Dim pidl2 As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.ILIsEqual(pidl1, 
	pidl2)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true, SetLastError = true)]
static bool ILIsEqual(
	IntPtr pidl1, 
	IntPtr pidl2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)>]
static member ILIsEqual : 
        pidl1 : IntPtr * 
        pidl2 : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>pidl1</dt><dd>Type: System.IntPtr<br />The first ITEMIDLIST structure.</dd><dt>pidl2</dt><dd>Type: System.IntPtr<br />The second ITEMIDLIST structure.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the two structures are equal, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilisequal" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilisequal</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />