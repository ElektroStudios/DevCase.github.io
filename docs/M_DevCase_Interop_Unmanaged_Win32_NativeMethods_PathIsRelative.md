# NativeMethods.PathIsRelative Method 
 

Searches a path and determines if it is relative.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathIsRelative(
	string path
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathIsRelative ( 
	path As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As String
Dim returnValue As Boolean

returnValue = NativeMethods.PathIsRelative(path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathIsRelative(
	String^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathIsRelative : 
        path : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.String<br />A pointer to a null-terminated string of maximum length MAX_PATH that contains the path to search.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the path is relative, or `false` (`False` in Visual Basic) if it is absolute.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathisrelativea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathisrelativea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />