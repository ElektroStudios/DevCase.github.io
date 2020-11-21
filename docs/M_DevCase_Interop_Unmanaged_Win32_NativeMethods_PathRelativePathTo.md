# NativeMethods.PathRelativePathTo Method 
 

Creates a relative path from one file or folder to another.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathRelativePathTo(
	StringBuilder path,
	string from,
	FileAttributes attrFrom,
	string to,
	FileAttributes attrTo
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathRelativePathTo ( 
	path As StringBuilder,
	from As String,
	attrFrom As FileAttributes,
	to As String,
	attrTo As FileAttributes
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilder
Dim from As String
Dim attrFrom As FileAttributes
Dim to As String
Dim attrTo As FileAttributes
Dim returnValue As Boolean

returnValue = NativeMethods.PathRelativePathTo(path, 
	from, attrFrom, to, attrTo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathRelativePathTo(
	StringBuilder^ path, 
	String^ from, 
	FileAttributes attrFrom, 
	String^ to, 
	FileAttributes attrTo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathRelativePathTo : 
        path : StringBuilder * 
        from : string * 
        attrFrom : FileAttributes * 
        to : string * 
        attrTo : FileAttributes -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A string buffer that receives the relative path. 

 This buffer must be at least MAX_PATH characters in size.</dd><dt>from</dt><dd>Type: System.String<br />A null-terminated string of maximum length MAX_PATH that contains the path that defines the start of the relative path.</dd><dt>attrFrom</dt><dd>Type: System.IO.FileAttributes<br />The file attributes of *from* parameter. 

 If this value contains Directory, *from* parameter is assumed to be a directory; otherwise, *from* parameter is assumed to be a file.</dd><dt>to</dt><dd>Type: System.String<br />\[Missing <param name="to"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.PathRelativePathTo(System.Text.StringBuilder,System.String,System.IO.FileAttributes,System.String,System.IO.FileAttributes)"\]</dd><dt>attrTo</dt><dd>Type: System.IO.FileAttributes<br />The file attributes of *[to]* parameter. 

 If this value contains Directory, *[to]* parameter is assumed to be directory; otherwise, *[to]* parameter is assumed to be a file.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathrelativepathtoa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathrelativepathtoa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />