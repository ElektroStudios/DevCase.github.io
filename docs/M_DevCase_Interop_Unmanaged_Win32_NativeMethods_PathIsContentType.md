# NativeMethods.PathIsContentType Method 
 

Determines if a file's registered content type matches the specified content type. 

 This function obtains the content type for the specified file type and compares that string with the *contentType*. The comparison is not case-sensitive.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathIsContentType(
	string path,
	string contentType
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathIsContentType ( 
	path As String,
	contentType As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As String
Dim contentType As String
Dim returnValue As Boolean

returnValue = NativeMethods.PathIsContentType(path, 
	contentType)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathIsContentType(
	String^ path, 
	String^ contentType
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathIsContentType : 
        path : string * 
        contentType : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.String<br />A pointer to a null-terminated string of maximum length MAX_PATH that contains the file whose content type will be compared.</dd><dt>contentType</dt><dd>Type: System.String<br />The address of a character buffer that contains the null-terminated content type string to which the file's registered content type will be compared.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the file's registered content type matches *contentType*, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/es-es/silverlight/bb773617(v=vs.100)" target="_blank">https://msdn.microsoft.com/es-es/silverlight/bb773617(v=vs.100)</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />