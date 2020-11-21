# NativeMethods.PathRemoveExtension Method 
 

**Note: This API is now obsolete.**

Removes the file name extension from a path, if one is present. 

 Note: This function is deprecated. We recommend the use of the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchRemoveExtension">PathCchRemoveExtension(StringBuilder, UInt32)</a> function in its place.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveExtension in its place.", 
	false)]
public static void PathRemoveExtension(
	StringBuilder path
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveExtension in its place.", 
	false)>
Public Shared Sub PathRemoveExtension ( 
	path As StringBuilder
)
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilderNativeMethods.PathRemoveExtension(path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveExtension in its place.", 
	false)]
static void PathRemoveExtension(
	StringBuilder^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveExtension in its place.", 
	false)>]
static member PathRemoveExtension : 
        path : StringBuilder -> unit 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a null-terminated string of length MAX_PATH from which to remove the extension.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathremoveextensiona" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathremoveextensiona</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />