# NativeMethods.PathAppend Method 
 

**Note: This API is now obsolete.**

Appends one path to the end of another. 

 Note: Misuse of this function can lead to a buffer overrun. We recommend the use of the safer <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchAppend">PathCchAppend(StringBuilder, UInt32, String)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchAppendEx">PathCchAppendEx(StringBuilder, UInt32, String, PathOptions)</a> function in its place.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAppend or NativeMethods.PathCchAppendEx function in its place.", 
	false)]
public static bool PathAppend(
	StringBuilder path,
	string more
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAppend or NativeMethods.PathCchAppendEx function in its place.", 
	false)>
Public Shared Function PathAppend ( 
	path As StringBuilder,
	more As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilder
Dim more As String
Dim returnValue As Boolean

returnValue = NativeMethods.PathAppend(path, 
	more)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAppend or NativeMethods.PathCchAppendEx function in its place.", 
	false)]
static bool PathAppend(
	StringBuilder^ path, 
	String^ more
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAppend or NativeMethods.PathCchAppendEx function in its place.", 
	false)>]
static member PathAppend : 
        path : StringBuilder * 
        more : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a null-terminated string to which the path specified in *more* is appended. 

 You must set the size of this buffer to MAX_PATH to ensure that it is large enough to hold the returned string.</dd><dt>more</dt><dd>Type: System.String<br />A pointer to a null-terminated string of maximum length MAX_PATH that contains the path to be appended.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathappenda" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathappenda</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />