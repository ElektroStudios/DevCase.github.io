# NativeMethods.PathIsSameRoot Method 
 

Compares two paths to determine if they have a common root component.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathIsSameRoot(
	string path1,
	string path2
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathIsSameRoot ( 
	path1 As String,
	path2 As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path1 As String
Dim path2 As String
Dim returnValue As Boolean

returnValue = NativeMethods.PathIsSameRoot(path1, 
	path2)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathIsSameRoot(
	String^ path1, 
	String^ path2
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathIsSameRoot : 
        path1 : string * 
        path2 : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>path1</dt><dd>Type: System.String<br />A pointer to a null-terminated string of maximum length MAX_PATH that contains the first path to be compared.</dd><dt>path2</dt><dd>Type: System.String<br />A pointer to a null-terminated string of maximum length MAX_PATH that contains the second path to be compared.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if both strings have the same root component, or `false` (`False` in Visual Basic) otherwise. 

 If *path1* contains only the server and share, this function also returns `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathissameroota" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathissameroota</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />