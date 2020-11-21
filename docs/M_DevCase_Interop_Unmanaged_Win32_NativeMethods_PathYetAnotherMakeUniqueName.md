# NativeMethods.PathYetAnotherMakeUniqueName Method 
 

Creates a unique filename based on an existing filename.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathYetAnotherMakeUniqueName(
	StringBuilder uniqueName,
	string path,
	string shortName,
	string fileSpec
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathYetAnotherMakeUniqueName ( 
	uniqueName As StringBuilder,
	path As String,
	shortName As String,
	fileSpec As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim uniqueName As StringBuilder
Dim path As String
Dim shortName As String
Dim fileSpec As String
Dim returnValue As Boolean

returnValue = NativeMethods.PathYetAnotherMakeUniqueName(uniqueName, 
	path, shortName, fileSpec)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathYetAnotherMakeUniqueName(
	StringBuilder^ uniqueName, 
	String^ path, 
	String^ shortName, 
	String^ fileSpec
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathYetAnotherMakeUniqueName : 
        uniqueName : StringBuilder * 
        path : string * 
        shortName : string * 
        fileSpec : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>uniqueName</dt><dd>Type: System.Text.StringBuilder<br />A string buffer that receives a null-terminated Unicode string that contains the fully qualified path of the unique file name. 

 This buffer should be at least MAX_PATH characters long to avoid causing a buffer overrun.</dd><dt>path</dt><dd>Type: System.String<br />A null-terminated Unicode string that contains the fully qualified path of folder that will contain the new file. 

 If *shortName* is set to NULL, this string must contain a full destination path, ending with the long file name that the new file name will be base on.</dd><dt>shortName</dt><dd>Type: System.String<br />A null-terminated Unicode string that contains the short file name that the unique name will be based on. 

 Set this value to NULL to create a name based on the long file name.</dd><dt>fileSpec</dt><dd>Type: System.String<br />A null-terminated Unicode string that contains the long file name that the unique name will be based on.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if a unique name was successfully created; otherwise `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pathyetanothermakeuniquename" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pathyetanothermakeuniquename</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />