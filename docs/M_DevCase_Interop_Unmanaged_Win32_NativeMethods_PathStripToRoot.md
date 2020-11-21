# NativeMethods.PathStripToRoot Method 
 

**Note: This API is now obsolete.**

Removes all file and directory elements in a path except for the root information. 

 Note: Misuse of this function can lead to a buffer overrun. We recommend the use of the safer <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchStripToRoot">PathCchStripToRoot(StringBuilder, UInt32)</a> function in its place.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchStripToRoot function in its place.", 
	false)]
public static bool PathStripToRoot(
	StringBuilder path
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchStripToRoot function in its place.", 
	false)>
Public Shared Function PathStripToRoot ( 
	path As StringBuilder
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilder
Dim returnValue As Boolean

returnValue = NativeMethods.PathStripToRoot(path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchStripToRoot function in its place.", 
	false)]
static bool PathStripToRoot(
	StringBuilder^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchStripToRoot function in its place.", 
	false)>]
static member PathStripToRoot : 
        path : StringBuilder -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a null-terminated string of length MAX_PATH that contains the path to be converted. 

 When this function returns successfully, this string contains only the root information taken from that path.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if a valid drive letter was found in the path, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathstriptoroota" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathstriptoroota</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />