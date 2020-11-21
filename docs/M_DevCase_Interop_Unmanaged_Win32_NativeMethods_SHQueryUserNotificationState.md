# NativeMethods.SHQueryUserNotificationState Method 
 

Checks the state of the computer for the current user to determine whether sending a notification is appropriate.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll")]
public static HResult SHQueryUserNotificationState(
	out QueryUserNotificationState refState
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll">]
Public Shared Function SHQueryUserNotificationState ( 
	<OutAttribute> ByRef refState As QueryUserNotificationState
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim refState As QueryUserNotificationState
Dim returnValue As HResult

returnValue = NativeMethods.SHQueryUserNotificationState(refState)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll")]
static HResult SHQueryUserNotificationState(
	[OutAttribute] QueryUserNotificationState% refState
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll")>]
static member SHQueryUserNotificationState : 
        refState : QueryUserNotificationState byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_QueryUserNotificationState">DevCase.Interop.Unmanaged.Win32.Enums.QueryUserNotificationState</a><br />When this function returns, contains one of the values of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_QueryUserNotificationState">QueryUserNotificationState</a> enumeration.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-shqueryusernotificationstate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-shqueryusernotificationstate</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />