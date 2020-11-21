# NativeMethods.PathCanonicalize Method 
 

**Note: This API is now obsolete.**

Simplifies a path by removing navigation elements such as "." and ".." to produce a direct, well-formed path. 

 Note: Misuse of this function can lead to a buffer overrun. We recommend the use of the safer <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchCanonicalize">PathCchCanonicalize(StringBuilder, UInt32, String)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchCanonicalizeEx">PathCchCanonicalizeEx(StringBuilder, UInt32, String, PathOptions)</a> function in its place.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchCanonicalize or NativeMethods.PathCchCanonicalizeEx function in its place.", 
	false)]
public static bool PathCanonicalize(
	StringBuilder buffer,
	string path
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchCanonicalize or NativeMethods.PathCchCanonicalizeEx function in its place.", 
	false)>
Public Shared Function PathCanonicalize ( 
	buffer As StringBuilder,
	path As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim path As String
Dim returnValue As Boolean

returnValue = NativeMethods.PathCanonicalize(buffer, 
	path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchCanonicalize or NativeMethods.PathCchCanonicalizeEx function in its place.", 
	false)]
static bool PathCanonicalize(
	StringBuilder^ buffer, 
	String^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchCanonicalize or NativeMethods.PathCchCanonicalizeEx function in its place.", 
	false)>]
static member PathCanonicalize : 
        buffer : StringBuilder * 
        path : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a string that receives the canonicalized path. 

 You must set the size of this buffer to MAX_PATH to ensure that it is large enough to hold the returned string.</dd><dt>path</dt><dd>Type: System.String<br />A pointer to a null-terminated string of maximum length MAX_PATH that contains the path to be canonicalized.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if a result has been computed and the content of the *buffer* output buffer is valid. 

 Returns `false` (`False` in Visual Basic) otherwise, and the contents of the buffer pointed to by *buffer* are invalid.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathcanonicalizea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathcanonicalizea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />