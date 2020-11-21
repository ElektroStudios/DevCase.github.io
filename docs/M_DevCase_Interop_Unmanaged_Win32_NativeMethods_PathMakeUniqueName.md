# NativeMethods.PathMakeUniqueName Method 
 

Creates a unique path name from a template.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathMakeUniqueName(
	StringBuilder uniqueName,
	uint uniqueNameMax,
	string shortTemplate,
	string longTemplate,
	string dir
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathMakeUniqueName ( 
	uniqueName As StringBuilder,
	uniqueNameMax As UInteger,
	shortTemplate As String,
	longTemplate As String,
	dir As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim uniqueName As StringBuilder
Dim uniqueNameMax As UInteger
Dim shortTemplate As String
Dim longTemplate As String
Dim dir As String
Dim returnValue As Boolean

returnValue = NativeMethods.PathMakeUniqueName(uniqueName, 
	uniqueNameMax, shortTemplate, longTemplate, 
	dir)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathMakeUniqueName(
	StringBuilder^ uniqueName, 
	unsigned int uniqueNameMax, 
	String^ shortTemplate, 
	String^ longTemplate, 
	String^ dir
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathMakeUniqueName : 
        uniqueName : StringBuilder * 
        uniqueNameMax : uint32 * 
        shortTemplate : string * 
        longTemplate : string * 
        dir : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>uniqueName</dt><dd>Type: System.Text.StringBuilder<br />A buffer that receives a null-terminated Unicode string that contains the unique path name. 

 It should be at least MAX_PATH characters in length.</dd><dt>uniqueNameMax</dt><dd>Type: System.UInt32<br />The number of characters in the buffer pointed to by *uniqueName*.</dd><dt>shortTemplate</dt><dd>Type: System.String<br />A null-terminated Unicode string that contains a template that is used to construct the unique name. 

 This template is used for drives that require file names with the 8.3 format. 

 This string should be no more than MAX_PATH characters in length, including the terminating null character.</dd><dt>longTemplate</dt><dd>Type: System.String<br />A null-terminated Unicode string that contains a template that is used to construct the unique name. 

 This template is used for drives that support long file names. 

 This string should be no more than MAX_PATH characters in length, including the terminating null character.</dd><dt>dir</dt><dd>Type: System.String<br />A null-terminated string that contains the directory in which the new file resides. 

 This string should be no more than MAX_PATH characters in length, including the terminating null character.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pathmakeuniquename" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pathmakeuniquename</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />