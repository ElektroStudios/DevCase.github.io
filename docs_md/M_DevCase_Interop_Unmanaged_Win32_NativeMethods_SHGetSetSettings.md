# NativeMethods.SHGetSetSettings Method 
 

Sets or retrieves Shell state settings. 

 This function may be altered or unavailable in subsequent Windows versions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", SetLastError = true)]
public static void SHGetSetSettings(
	out ShellState refState,
	ShellStateFlags mask,
	bool applyState
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", SetLastError := true>]
Public Shared Sub SHGetSetSettings ( 
	<OutAttribute> ByRef refState As ShellState,
	mask As ShellStateFlags,
	applyState As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim refState As ShellState
Dim mask As ShellStateFlags
Dim applyState As BooleanNativeMethods.SHGetSetSettings(refState, 
	mask, applyState)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", SetLastError = true)]
static void SHGetSetSettings(
	[InAttribute] [OutAttribute] ShellState% refState, 
	ShellStateFlags mask, 
	bool applyState
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", SetLastError = true)>]
static member SHGetSetSettings : 
        refState : ShellState byref * 
        mask : ShellStateFlags * 
        applyState : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>refState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellState">DevCase.Interop.Unmanaged.Win32.Structures.ShellState</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellState">ShellState</a> structure that provides or receives the Shell state settings.</dd><dt>mask</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellStateFlags">DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags</a><br />One or more of the SSF flags that indicate which settings should be set or retrieved.</dd><dt>applyState</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to indicate that the contents of lpss should be used to set the Shell settings, `false` (`False` in Visual Basic) to indicate that the Shell settings should be retrieved to lpss.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/bb759788%28v=VS.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/bb759788%28v=VS.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />