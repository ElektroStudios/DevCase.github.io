# NativeMethods.PathRenameExtension Method 
 

**Note: This API is now obsolete.**

Replaces the extension of a file name with a new extension. 

 If the file name does not contain an extension, the extension will be attached to the end of the string. 

 Note: Misuse of this function can lead to a buffer overrun. We recommend the use of the safer <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchRenameExtension">PathCchRenameExtension(StringBuilder, UInt32, String)</a> function in its place.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchRenameExtension function in its place.", 
	false)]
public static bool PathRenameExtension(
	StringBuilder path,
	string ext
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchRenameExtension function in its place.", 
	false)>
Public Shared Function PathRenameExtension ( 
	path As StringBuilder,
	ext As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilder
Dim ext As String
Dim returnValue As Boolean

returnValue = NativeMethods.PathRenameExtension(path, 
	ext)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchRenameExtension function in its place.", 
	false)]
static bool PathRenameExtension(
	StringBuilder^ path, 
	String^ ext
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchRenameExtension function in its place.", 
	false)>]
static member PathRenameExtension : 
        path : StringBuilder * 
        ext : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a null-terminated string of length MAX_PATH in which to replace the extension.</dd><dt>ext</dt><dd>Type: System.String<br />Pointer to a character buffer that contains a '.' character followed by the new extension.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) if the new path and extension would exceed MAX_PATH characters.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathrenameextensiona" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathrenameextensiona</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />