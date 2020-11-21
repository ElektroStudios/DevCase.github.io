# NativeMethods.PathBuildRoot Method 
 

Creates a root path from a given drive number.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr PathBuildRoot(
	StringBuilder root,
	int driveIndex
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathBuildRoot ( 
	root As StringBuilder,
	driveIndex As Integer
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim root As StringBuilder
Dim driveIndex As Integer
Dim returnValue As IntPtr

returnValue = NativeMethods.PathBuildRoot(root, 
	driveIndex)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr PathBuildRoot(
	StringBuilder^ root, 
	int driveIndex
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathBuildRoot : 
        root : StringBuilder * 
        driveIndex : int -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>root</dt><dd>Type: System.Text.StringBuilder<br />A pointer to the string that receives the constructed root path. This buffer must be at least four characters in size.</dd><dt>driveIndex</dt><dd>Type: System.Int32<br />A variable of type int that indicates the desired drive number. It should be between 0 and 25.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns the address of the constructed root path. 

 If the call fails for any reason (for example, an invalid drive number), *root* is returned unchanged.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathbuildroota" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathbuildroota</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />