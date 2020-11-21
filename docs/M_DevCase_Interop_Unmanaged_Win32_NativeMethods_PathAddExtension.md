# NativeMethods.PathAddExtension Method 
 

**Note: This API is now obsolete.**

Adds a file name extension to a path string. 

 Note: Misuse of this function can lead to a buffer overrun. We recommend the use of the safer <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchAddExtension">PathCchAddExtension(StringBuilder, UInt32, String)</a> function in its place.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAddExtension function in its place.", 
	false)]
public static bool PathAddExtension(
	StringBuilder path,
	string ext
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAddExtension function in its place.", 
	false)>
Public Shared Function PathAddExtension ( 
	path As StringBuilder,
	ext As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilder
Dim ext As String
Dim returnValue As Boolean

returnValue = NativeMethods.PathAddExtension(path, 
	ext)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAddExtension function in its place.", 
	false)]
static bool PathAddExtension(
	StringBuilder^ path, 
	String^ ext
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchAddExtension function in its place.", 
	false)>]
static member PathAddExtension : 
        path : StringBuilder * 
        ext : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer with the null-terminated string to which the file name extension will be appended. 

 You must set the size of this buffer to MAX_PATH to ensure that it is large enough to hold the returned string.</dd><dt>ext</dt><dd>Type: System.String<br />A pointer to a null-terminated string that contains the file name extension. This value can be NULL.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if an extension was added, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathaddextensiona" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathaddextensiona</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />