# NativeMethods.SHGetPathFromIDList Method 
 

Converts an item identifier list to a file system path.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SHGetPathFromIDList(
	IntPtr pidl,
	StringBuilder path
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SHGetPathFromIDList ( 
	pidl As IntPtr,
	path As StringBuilder
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pidl As IntPtr
Dim path As StringBuilder
Dim returnValue As Boolean

returnValue = NativeMethods.SHGetPathFromIDList(pidl, 
	path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SHGetPathFromIDList(
	IntPtr pidl, 
	StringBuilder^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SHGetPathFromIDList : 
        pidl : IntPtr * 
        path : StringBuilder -> bool 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />The address of an item identifier list that specifies a file or directory location relative to the root of the namespace (the desktop).</dd><dt>path</dt><dd>Type: System.Text.StringBuilder<br />The address of a buffer to receive the file system path. 

 This buffer must be at least `MAX_PATH` characters in size.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if successful; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762194(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762194(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />