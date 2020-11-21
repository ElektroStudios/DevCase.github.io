# NativeMethods.ShellExecuteEx Method 
 

Performs an operation on a specified file..

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static bool ShellExecuteEx(
	ref ShellExecuteInfo refExecInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function ShellExecuteEx ( 
	ByRef refExecInfo As ShellExecuteInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refExecInfo As ShellExecuteInfo
Dim returnValue As Boolean

returnValue = NativeMethods.ShellExecuteEx(refExecInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static bool ShellExecuteEx(
	ShellExecuteInfo% refExecInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member ShellExecuteEx : 
        refExecInfo : ShellExecuteInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refExecInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">DevCase.Interop.Unmanaged.Win32.Structures.ShellExecuteInfo</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo</a> structure that contains and receives information about the application being executed.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if successful, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762154%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762154%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />