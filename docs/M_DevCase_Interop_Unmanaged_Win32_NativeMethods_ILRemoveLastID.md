# NativeMethods.ILRemoveLastID Method 
 

Removes the last SHITEMID structure from an ITEMIDLIST structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ILRemoveLastID(
	IntPtr pidl
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ILRemoveLastID ( 
	pidl As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pidl As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.ILRemoveLastID(pidl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true, SetLastError = true)]
static bool ILRemoveLastID(
	IntPtr pidl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)>]
static member ILRemoveLastID : 
        pidl : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />A pointer to the ITEMIDLIST structure to be shortened. 

 When the function returns, this variable points to the shortened structure.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilremovelastid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilremovelastid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />