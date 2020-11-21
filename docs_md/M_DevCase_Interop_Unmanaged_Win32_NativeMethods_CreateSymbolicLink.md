# NativeMethods.CreateSymbolicLink Method 
 

Creates a symbolic link.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static bool CreateSymbolicLink(
	string dstPath,
	string srcPath,
	SymbolicLinkFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, SetLastError := true>]
Public Shared Function CreateSymbolicLink ( 
	dstPath As String,
	srcPath As String,
	flags As SymbolicLinkFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim dstPath As String
Dim srcPath As String
Dim flags As SymbolicLinkFlags
Dim returnValue As Boolean

returnValue = NativeMethods.CreateSymbolicLink(dstPath, 
	srcPath, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, SetLastError = true)]
static bool CreateSymbolicLink(
	String^ dstPath, 
	String^ srcPath, 
	SymbolicLinkFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)>]
static member CreateSymbolicLink : 
        dstPath : string * 
        srcPath : string * 
        flags : SymbolicLinkFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>dstPath</dt><dd>Type: System.String<br />The path of the symbolic link to be created.</dd><dt>srcPath</dt><dd>Type: System.String<br />The path of the target for the symbolic link to be created. 

 If *srcPath* has a device name associated with it, the link is treated as an absolute link; otherwise, the link is treated as a relative link.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SymbolicLinkFlags">DevCase.Interop.Unmanaged.Win32.Enums.SymbolicLinkFlags</a><br />Indicates whether the link target is a file or is a directory.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 



## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa363866%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa363866%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />