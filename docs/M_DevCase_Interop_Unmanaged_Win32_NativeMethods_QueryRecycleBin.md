# NativeMethods.QueryRecycleBin Method 
 

Retrieves the accumulated size of the Recycle Bin and the number of items in it, for a specified drive.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", EntryPoint = "SHQueryRecycleBin", 
	CharSet = CharSet.Unicode)]
public static bool QueryRecycleBin(
	string rootPath,
	ref SHQueryRBInfo refQueryRBInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", EntryPoint := "SHQueryRecycleBin", 
	CharSet := CharSet.Unicode>]
Public Shared Function QueryRecycleBin ( 
	rootPath As String,
	ByRef refQueryRBInfo As SHQueryRBInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim rootPath As String
Dim refQueryRBInfo As SHQueryRBInfo
Dim returnValue As Boolean

returnValue = NativeMethods.QueryRecycleBin(rootPath, 
	refQueryRBInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", EntryPoint = L"SHQueryRecycleBin", 
	CharSet = CharSet::Unicode)]
static bool QueryRecycleBin(
	String^ rootPath, 
	SHQueryRBInfo% refQueryRBInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", EntryPoint = "SHQueryRecycleBin", 
	CharSet = CharSet.Unicode)>]
static member QueryRecycleBin : 
        rootPath : string * 
        refQueryRBInfo : SHQueryRBInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>rootPath</dt><dd>Type: System.String<br />The address of a null-terminated string of maximum length MAX_PATH to contain the path of the root drive on which the Recycle Bin is located. 

 This parameter can contain the address of a string formatted with the drive, folder, and subfolder names (C:\Windows\System32\).</dd><dt>refQueryRBInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SHQueryRBInfo">DevCase.Interop.Unmanaged.Win32.Structures.SHQueryRBInfo</a><br />The address of a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SHQueryRBInfo">SHQueryRBInfo</a> structure that receives the Recycle Bin information. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SHQueryRBInfo_SizeOfStruct">SizeOfStruct</a> member of the structure must be set to the size of the structure before calling this API.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762241%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762241%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />