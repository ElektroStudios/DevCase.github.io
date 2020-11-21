# NativeMethods.SetComputerNameEx Method 
 

Sets a new NetBIOS or DNS name for the local computer. 

 Name changes made by SetComputerNameEx(ComputerNameFormat, String) do not take effect until the user restarts the computer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SetComputerNameEx(
	ComputerNameFormat nameFormat,
	string computerName
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SetComputerNameEx ( 
	nameFormat As ComputerNameFormat,
	computerName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim nameFormat As ComputerNameFormat
Dim computerName As String
Dim returnValue As Boolean

returnValue = NativeMethods.SetComputerNameEx(nameFormat, 
	computerName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SetComputerNameEx(
	ComputerNameFormat nameFormat, 
	[InAttribute] String^ computerName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SetComputerNameEx : 
        nameFormat : ComputerNameFormat * 
        computerName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>nameFormat</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ComputerNameFormat">DevCase.Interop.Unmanaged.Win32.Enums.ComputerNameFormat</a><br />The type of name to be set.</dd><dt>computerName</dt><dd>Type: System.String<br />The new name. 

 The name cannot include control characters, leading or trailing spaces, or any of the following characters: " / \ [ ] : | < > + = ; , ?</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is a `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms724931(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms724931(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />