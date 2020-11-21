# NativeMethods.PathRemoveFileSpec Method 
 

**Note: This API is now obsolete.**

Removes the trailing file name and backslash from a path, if they are present. 

 Note: This function is deprecated. We recommend the use of the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchRemoveFileSpec">PathCchRemoveFileSpec(StringBuilder, UInt32)</a> function in its place.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveFileSpec function in its place.", 
	false)]
public static bool PathRemoveFileSpec(
	StringBuilder path
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveFileSpec function in its place.", 
	false)>
Public Shared Function PathRemoveFileSpec ( 
	path As StringBuilder
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilder
Dim returnValue As Boolean

returnValue = NativeMethods.PathRemoveFileSpec(path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveFileSpec function in its place.", 
	false)]
static bool PathRemoveFileSpec(
	StringBuilder^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveFileSpec function in its place.", 
	false)>]
static member PathRemoveFileSpec : 
        path : StringBuilder -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a null-terminated string of length MAX_PATH that contains the path from which to remove the file name.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if something was removed, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathremovefilespeca" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathremovefilespeca</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />