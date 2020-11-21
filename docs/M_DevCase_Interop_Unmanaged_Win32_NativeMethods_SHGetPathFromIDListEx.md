# NativeMethods.SHGetPathFromIDListEx Method 
 

Converts an item identifier list to a file system path. 

 This function extends <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetPathFromIDList">SHGetPathFromIDList(IntPtr, StringBuilder)</a> by allowing you to set the initial size of the string buffer and declare the options below.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SHGetPathFromIDListEx(
	IntPtr pidl,
	StringBuilder path,
	uint pathSize,
	GetPathFromIdListOption option
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SHGetPathFromIDListEx ( 
	pidl As IntPtr,
	path As StringBuilder,
	pathSize As UInteger,
	option As GetPathFromIdListOption
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pidl As IntPtr
Dim path As StringBuilder
Dim pathSize As UInteger
Dim option As GetPathFromIdListOption
Dim returnValue As Boolean

returnValue = NativeMethods.SHGetPathFromIDListEx(pidl, 
	path, pathSize, option)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SHGetPathFromIDListEx(
	IntPtr pidl, 
	StringBuilder^ path, 
	unsigned int pathSize, 
	GetPathFromIdListOption option
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SHGetPathFromIDListEx : 
        pidl : IntPtr * 
        path : StringBuilder * 
        pathSize : uint32 * 
        option : GetPathFromIdListOption -> bool 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />The address of an item identifier list that specifies a file or directory location relative to the root of the namespace (the desktop).</dd><dt>path</dt><dd>Type: System.Text.StringBuilder<br />The address of a buffer to receive the file system path. 

 This buffer must be at least `MAX_PATH` characters in size.</dd><dt>pathSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *path* parameter, in characters.</dd><dt>option</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GetPathFromIdListOption">DevCase.Interop.Unmanaged.Win32.Enums.GetPathFromIdListOption</a><br />Determine the type of path returned.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if successful; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shgetpathfromidlistex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shgetpathfromidlistex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />