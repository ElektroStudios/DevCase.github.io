# NativeMethods.ILIsParent Method 
 

Tests whether an ITEMIDLIST structure is the parent of another ITEMIDLIST structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ILIsParent(
	IntPtr pidl1,
	IntPtr pidl2,
	bool immediate
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ILIsParent ( 
	pidl1 As IntPtr,
	pidl2 As IntPtr,
	immediate As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pidl1 As IntPtr
Dim pidl2 As IntPtr
Dim immediate As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.ILIsParent(pidl1, 
	pidl2, immediate)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true, SetLastError = true)]
static bool ILIsParent(
	IntPtr pidl1, 
	IntPtr pidl2, 
	bool immediate
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)>]
static member ILIsParent : 
        pidl1 : IntPtr * 
        pidl2 : IntPtr * 
        immediate : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>pidl1</dt><dd>Type: System.IntPtr<br />A pointer to an ITEMIDLIST (PIDL) structure that specifies the parent. This must be an absolute PIDL.</dd><dt>pidl2</dt><dd>Type: System.IntPtr<br />A pointer to an ITEMIDLIST (PIDL) structure that specifies the child. This must be an absolute PIDL.</dd><dt>immediate</dt><dd>Type: System.Boolean<br />A Boolean value that is set to `true` (`True` in Visual Basic) to test for immediate parents of *pidl2*, or `false` (`False` in Visual Basic) to test for any parents of *pidl2*.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if *pidl1* is a parent of *pidl2*. 

 If fImmediate is set to `true` (`True` in Visual Basic), the function only returns `true` (`True` in Visual Basic) if *pidl1* is the immediate parent of *pidl2*. Otherwise, the function returns `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilisparent" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilisparent</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />