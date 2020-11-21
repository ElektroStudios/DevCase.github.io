# NativeMethods.PathCombine Method 
 

**Note: This API is now obsolete.**

Concatenates two strings that represent properly formed paths into one path; also concatenates any relative path elements. 

 Note: Misuse of this function can lead to a buffer overrun. We recommend the use of the safer <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchCombine">PathCchCombine(StringBuilder, UInt32, String, String)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchCombineEx">PathCchCombineEx(StringBuilder, UInt32, String, String, PathOptions)</a> function in its place.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchCombine or NativeMethods.PathCchCombineEx function in its place.", 
	false)]
public static IntPtr PathCombine(
	StringBuilder destination,
	string dir,
	string file
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchCombine or NativeMethods.PathCchCombineEx function in its place.", 
	false)>
Public Shared Function PathCombine ( 
	destination As StringBuilder,
	dir As String,
	file As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim destination As StringBuilder
Dim dir As String
Dim file As String
Dim returnValue As IntPtr

returnValue = NativeMethods.PathCombine(destination, 
	dir, file)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchCombine or NativeMethods.PathCchCombineEx function in its place.", 
	false)]
static IntPtr PathCombine(
	StringBuilder^ destination, 
	String^ dir, 
	String^ file
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("Misuse of this function can lead to a buffer overrun. We recommend the use of the safer NativeMethods.PathCchCombine or NativeMethods.PathCchCombineEx function in its place.", 
	false)>]
static member PathCombine : 
        destination : StringBuilder * 
        dir : string * 
        file : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>destination</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that, when this function returns successfully, receives the combined path string. 

 You must set the size of this buffer to MAX_PATH to ensure that it is large enough to hold the returned string.</dd><dt>dir</dt><dd>Type: System.String<br />A pointer to a null-terminated string of maximum length MAX_PATH that contains the first path. This value can be NULL.</dd><dt>file</dt><dd>Type: System.String<br />A pointer to a null-terminated string of maximum length MAX_PATH that contains the second path. This value can be NULL.</dd></dl>

#### Return Value
Type: IntPtr<br />A pointer to a buffer that, when this function returns successfully, receives the concatenated path string. 

 This is the same string pointed to by *destination*. If this function does not return successfully, this value is NULL.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathcombinea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathcombinea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />