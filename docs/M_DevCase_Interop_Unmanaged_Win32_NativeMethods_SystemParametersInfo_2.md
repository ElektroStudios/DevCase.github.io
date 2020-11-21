# NativeMethods.SystemParametersInfo Method (SystemParametersActionFlags, Int32, UInt32, SystemParametersWinIniFlags)
 

Retrieves or sets the value of one of the system-wide parameters. 

 This function can also update the user profile while setting a parameter.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool SystemParametersInfo(
	SystemParametersActionFlags action,
	int uiParam,
	uint pvParam,
	SystemParametersWinIniFlags winIni
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SystemParametersInfo ( 
	action As SystemParametersActionFlags,
	uiParam As Integer,
	pvParam As UInteger,
	winIni As SystemParametersWinIniFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim action As SystemParametersActionFlags
Dim uiParam As Integer
Dim pvParam As UInteger
Dim winIni As SystemParametersWinIniFlags
Dim returnValue As Boolean

returnValue = NativeMethods.SystemParametersInfo(action, 
	uiParam, pvParam, winIni)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool SystemParametersInfo(
	SystemParametersActionFlags action, 
	int uiParam, 
	unsigned int pvParam, 
	SystemParametersWinIniFlags winIni
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SystemParametersInfo : 
        action : SystemParametersActionFlags * 
        uiParam : int * 
        pvParam : uint32 * 
        winIni : SystemParametersWinIniFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>action</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SystemParametersActionFlags">DevCase.Interop.Unmanaged.Win32.Enums.SystemParametersActionFlags</a><br />The system-wide parameter to be retrieved or set.</dd><dt>uiParam</dt><dd>Type: System.Int32<br />A parameter whose usage and format depends on the system parameter being queried or set. 

 For more information about system-wide parameters, see the  parameter; If not otherwise indicated, you must specify '0' for this parameter.</dd><dt>pvParam</dt><dd>Type: System.UInt32<br />A parameter whose usage and format depends on the system parameter being queried or set. 

 For more information about system-wide parameters, see the  parameter; If not otherwise indicated, you must specify a null reference (`Nothing` in Visual Basic) for this parameter. 

 For information on the `PVOID` datatype, see Windows Data Types.</dd><dt>winIni</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SystemParametersWinIniFlags">DevCase.Interop.Unmanaged.Win32.Enums.SystemParametersWinIniFlags</a><br />If a system parameter is being set, specifies whether the user profile is to be updated, and if so, whether the `WM_SETTINGCHANGE` message is to be broadcast to all top-level windows to notify them of the change. 

 This parameter can be '0' if you do not want to update the user profile or broadcast the `WM_SETTINGCHANGE` message.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms724947%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms724947%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SystemParametersInfo">SystemParametersInfo Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />