# NativeMethods.PathAddBackslash Method 
 

**Note: This API is now obsolete.**

Adds a backslash to the end of a string to create the correct syntax for a path. 

 If the source path already has a trailing backslash, no backslash will be added. 

 Note: Misuse of this function can lead to a buffer overrun. We recommend the use of the safer <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchAddBackslash">PathCchAddBackslash(StringBuilder, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchAddBackslashEx">PathCchAddBackslashEx(StringBuilder, UInt32, IntPtr, UInt32)</a> function in its place

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAddBackslash or NativeMethods.PathCchAddBackslashEx function in its place.", 
	false)]
public static IntPtr PathAddBackslash(
	StringBuilder path
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAddBackslash or NativeMethods.PathCchAddBackslashEx function in its place.", 
	false)>
Public Shared Function PathAddBackslash ( 
	path As StringBuilder
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilder
Dim returnValue As IntPtr

returnValue = NativeMethods.PathAddBackslash(path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAddBackslash or NativeMethods.PathCchAddBackslashEx function in its place.", 
	false)]
static IntPtr PathAddBackslash(
	StringBuilder^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAddBackslash or NativeMethods.PathCchAddBackslashEx function in its place.", 
	false)>]
static member PathAddBackslash : 
        path : StringBuilder -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer with a string that represents a path. 

 The size of this buffer must be set to MAX_PATH to ensure that it is large enough to hold the returned string.</dd></dl>

#### Return Value
Type: IntPtr<br />A pointer that, when this function returns successfully, points to the new string's terminating null character. 

 If the backslash could not be appended due to inadequate buffer size, this value is NULL.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathaddbackslasha" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathaddbackslasha</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />