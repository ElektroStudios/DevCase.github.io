# NativeMethods.SHGetNameFromIDList Method (IntPtr, ShellItemGetDisplayName, StringBuilder)
 

Retrieves the display name of an item identified by its IDList.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult SHGetNameFromIDList(
	IntPtr pidl,
	ShellItemGetDisplayName sigdn,
	out StringBuilder refName
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function SHGetNameFromIDList ( 
	pidl As IntPtr,
	sigdn As ShellItemGetDisplayName,
	<OutAttribute> ByRef refName As StringBuilder
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim pidl As IntPtr
Dim sigdn As ShellItemGetDisplayName
Dim refName As StringBuilder
Dim returnValue As HResult

returnValue = NativeMethods.SHGetNameFromIDList(pidl, 
	sigdn, refName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult SHGetNameFromIDList(
	IntPtr pidl, 
	ShellItemGetDisplayName sigdn, 
	[OutAttribute] StringBuilder^% refName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member SHGetNameFromIDList : 
        pidl : IntPtr * 
        sigdn : ShellItemGetDisplayName * 
        refName : StringBuilder byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />A PIDL that identifies the item.</dd><dt>sigdn</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemGetDisplayName">DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName</a><br />A value from the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemGetDisplayName">ShellItemGetDisplayName</a> enumeration that specifies the type of display name to retrieve.</dd><dt>refName</dt><dd>Type: System.Text.StringBuilder<br />A value that, when this function returns successfully, receives the retrieved display name.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. 

 Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shgetnamefromidlist" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shgetnamefromidlist</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetNameFromIDList">SHGetNameFromIDList Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />