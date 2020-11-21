# NativeMethods.PathRemoveBackslash Method 
 

**Note: This API is now obsolete.**

Removes the trailing backslash from a given path. 

 Note: This function is deprecated. We recommend the use of the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchRemoveBackslash">PathCchRemoveBackslash(StringBuilder, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchRemoveBackslashEx">PathCchRemoveBackslashEx(StringBuilder, UInt32, IntPtr, UInt32)</a> function in its place

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveBackslash or NativeMethods.PathCchRemoveBackslashEx function in its place.", 
	false)]
public static IntPtr PathRemoveBackslash(
	StringBuilder path
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveBackslash or NativeMethods.PathCchRemoveBackslashEx function in its place.", 
	false)>
Public Shared Function PathRemoveBackslash ( 
	path As StringBuilder
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilder
Dim returnValue As IntPtr

returnValue = NativeMethods.PathRemoveBackslash(path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveBackslash or NativeMethods.PathCchRemoveBackslashEx function in its place.", 
	false)]
static IntPtr PathRemoveBackslash(
	StringBuilder^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("This function is deprecated. We recommend the use of the NativeMethods.PathCchRemoveBackslash or NativeMethods.PathCchRemoveBackslashEx function in its place.", 
	false)>]
static member PathRemoveBackslash : 
        path : StringBuilder -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a null-terminated string of length MAX_PATH that contains the path from which to remove the backslash.</dd></dl>

#### Return Value
Type: IntPtr<br />A pointer that, when this function returns successfully and if a backslash has been removed, points to the terminating null character that has replaced the backslash at the end of the string. 

 If the path did not include a trailing backslash, this value will point to the final character in the string.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathremovebackslasha" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathremovebackslasha</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />