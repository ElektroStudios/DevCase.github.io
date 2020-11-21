# NativeMethods.SHUpdateImage Method 
 

Notifies the Shell that an image in the system image list has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static void SHUpdateImage(
	string filepath,
	int iconIndex,
	SHUpdateImageFlags flags,
	int imageIndex
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Sub SHUpdateImage ( 
	filepath As String,
	iconIndex As Integer,
	flags As SHUpdateImageFlags,
	imageIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim iconIndex As Integer
Dim flags As SHUpdateImageFlags
Dim imageIndex As Integer

NativeMethods.SHUpdateImage(filepath, iconIndex, 
	flags, imageIndex)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static void SHUpdateImage(
	String^ filepath, 
	int iconIndex, 
	SHUpdateImageFlags flags, 
	int imageIndex
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SHUpdateImage : 
        filepath : string * 
        iconIndex : int * 
        flags : SHUpdateImageFlags * 
        imageIndex : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />A pointer to a string value that specifies the fully qualified path of the file that contains the icon.</dd><dt>iconIndex</dt><dd>Type: System.Int32<br />An integer that specifies the zero-based index of the icon in the file specified by *filepath*.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHUpdateImageFlags">DevCase.Interop.Unmanaged.Win32.Enums.SHUpdateImageFlags</a><br />The flags that determine the icon attributes.</dd><dt>imageIndex</dt><dd>Type: System.Int32<br />An integer that specifies the index in the system image list of the icon that is being updated.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shupdateimagea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shupdateimagea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />