# NativeMethods.EmptyRecycleBin Method (IntPtr, String, SHEmptyRecycleBinFlags)
 

Empties the Recycle Bin on the specified drive.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", EntryPoint = "SHEmptyRecycleBin", 
	CharSet = CharSet.Unicode)]
public static bool EmptyRecycleBin(
	IntPtr hWnd = null,
	string rootPath = "",
	SHEmptyRecycleBinFlags flags = 
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", EntryPoint := "SHEmptyRecycleBin", 
	CharSet := CharSet.Unicode>]
Public Shared Function EmptyRecycleBin ( 
	Optional hWnd As IntPtr = Nothing,
	Optional rootPath As String = "",
	Optional flags As SHEmptyRecycleBinFlags = 
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim rootPath As String
Dim flags As SHEmptyRecycleBinFlags
Dim returnValue As Boolean

returnValue = NativeMethods.EmptyRecycleBin(hWnd, 
	rootPath, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", EntryPoint = L"SHEmptyRecycleBin", 
	CharSet = CharSet::Unicode)]
static bool EmptyRecycleBin(
	IntPtr hWnd = nullptr, 
	String^ rootPath = L"", 
	SHEmptyRecycleBinFlags flags = 
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", EntryPoint = "SHEmptyRecycleBin", 
	CharSet = CharSet.Unicode)>]
static member EmptyRecycleBin : 
        ?hWnd : IntPtr * 
        ?rootPath : string * 
        ?flags : SHEmptyRecycleBinFlags 
(* Defaults:
        let _hWnd = defaultArg hWnd null
        let _rootPath = defaultArg rootPath ""
        let _flags = defaultArg flags 
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd (Optional)</dt><dd>Type: System.IntPtr<br />A handle to the parent window of any dialog boxes that might be displayed during the operation. 

 This parameter can be a null reference (`Nothing` in Visual Basic).</dd><dt>rootPath (Optional)</dt><dd>Type: System.String<br />The address of a null-terminated string of maximum length MAX_PATH that contains the path of the root drive on which the Recycle Bin is located. 

 This parameter can contain the address of a string formatted with the drive, folder, and subfolder names, for example 'C:\windows\system\'. 

 It can also contain an empty string or a null reference (`Nothing` in Visual Basic). 

 If this value is an empty string or a null reference (`Nothing` in Visual Basic), all Recycle Bins on all drives will be emptied.</dd><dt>flags (Optional)</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHEmptyRecycleBinFlags">DevCase.Interop.Unmanaged.Win32.Enums.SHEmptyRecycleBinFlags</a><br />Specifies the Recycle bin behavior, this parameter can be one or more flags.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762160%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762160%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_EmptyRecycleBin">EmptyRecycleBin Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />