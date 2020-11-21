# NativeMethods.PathIsSystemFolder Method (String, UInt32)
 

Determines if an existing folder contains the attributes that make it a system folder. 

 Alternately, this function indicates if certain attributes qualify a folder to be a system folder.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathIsSystemFolder(
	string path,
	uint attributes
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathIsSystemFolder ( 
	path As String,
	attributes As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As String
Dim attributes As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.PathIsSystemFolder(path, 
	attributes)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathIsSystemFolder(
	String^ path, 
	unsigned int attributes
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathIsSystemFolder : 
        path : string * 
        attributes : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.String<br />A pointer to a null-terminated string of maximum length MAX_PATH that contains the name of an existing folder. 

 The attributes for this folder will be retrieved and compared with those that define a system folder. 

 If this folder contains the attributes to make it a system folder, the function returns nonzero. 

 If this value is NULL, this function determines if the attributes passed in *attributes* qualify it to be a system folder.</dd><dt>attributes</dt><dd>Type: System.UInt32<br />The file attributes to be compared. 

 Used only if *path* is NULL. In that case, the attributes passed in this value are compared with those that qualify a folder as a system folder. 

 If the attributes are sufficient to make this a system folder, this function returns `true` (`True` in Visual Basic). These attributes are the attributes that are returned from GetFileAttributes function.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the pszPath or *attributes* represent a system folder, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathissystemfoldera" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathissystemfoldera</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathIsSystemFolder">PathIsSystemFolder Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />