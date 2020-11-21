# NativeMethods.SetComputerName Method 
 

Sets a new NetBIOS name for the local computer. 

 The name is stored in the registry and the name change takes effect the next time the user restarts the computer. 

 If the local computer is a node in a cluster, SetComputerName(String) sets NetBIOS name of the local computer, not that of the cluster virtual server. 

 To set the DNS host name or the DNS domain name, call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetComputerNameEx">SetComputerNameEx(ComputerNameFormat, String)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SetComputerName(
	string computerName
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SetComputerName ( 
	computerName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim computerName As String
Dim returnValue As Boolean

returnValue = NativeMethods.SetComputerName(computerName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SetComputerName(
	[InAttribute] String^ computerName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SetComputerName : 
        computerName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>computerName</dt><dd>Type: System.String<br />The computer name that will take effect the next time the computer is started. 



 The standard character set includes letters, numbers, and the following symbols: 

 ! @ # $ % ^ & ' ) ( . - _ { } ~ . 

 If this parameter contains one or more characters that are outside the standard character set, SetComputerName(String) returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_INVALID_PARAMETER</a></dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is a `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms724930%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms724930%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />