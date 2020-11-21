# NativeMethods.SHGetDesktopFolder Method 
 

Retrieves the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder</a> interface for the desktop folder, which is the root of the Shell's namespace.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)]
[SecurityCriticalAttribute]
public static HResult SHGetDesktopFolder(
	out IShellFolder refShellFolder
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Unicode, ExactSpelling := true>]
<SecurityCriticalAttribute>
Public Shared Function SHGetDesktopFolder ( 
	<OutAttribute> ByRef refShellFolder As IShellFolder
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim refShellFolder As IShellFolder
Dim returnValue As HResult

returnValue = NativeMethods.SHGetDesktopFolder(refShellFolder)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Unicode, ExactSpelling = true)]
[SecurityCriticalAttribute]
static HResult SHGetDesktopFolder(
	[OutAttribute] IShellFolder^% refShellFolder
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)>]
[<SecurityCriticalAttribute>]
static member SHGetDesktopFolder : 
        refShellFolder : IShellFolder byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refShellFolder</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellFolder</a><br />When this method returns, receives an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder</a> interface pointer for the desktop folder. 

 The calling application is responsible for eventually freeing the interface by calling its IUnknown.Release method.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shgetdesktopfolder" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shgetdesktopfolder</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />