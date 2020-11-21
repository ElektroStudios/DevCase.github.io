# NativeMethods.SetCurrentProcessExplicitAppUserModelID Method 
 

Specifies a unique application-defined Application User Model ID (AppUserModelID) that identifies the current process to the taskbar. 

 This identifier allows an application to group its associated processes and windows under a single taskbar button. 

 This method must be called during an application's initial startup routine before the application presents any UI or makes any manipulation of its Jump Lists. This includes any call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHAddToRecentDocs">SHAddToRecentDocs(ShellAddToRecentDocsFlags, PIDL)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", SetLastError = true)]
public static int SetCurrentProcessExplicitAppUserModelID(
	string appID
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", SetLastError := true>]
Public Shared Function SetCurrentProcessExplicitAppUserModelID ( 
	appID As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim appID As String
Dim returnValue As Integer

returnValue = NativeMethods.SetCurrentProcessExplicitAppUserModelID(appID)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", SetLastError = true)]
static int SetCurrentProcessExplicitAppUserModelID(
	String^ appID
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", SetLastError = true)>]
static member SetCurrentProcessExplicitAppUserModelID : 
        appID : string -> int 

```


#### Parameters
&nbsp;<dl><dt>appID</dt><dd>Type: System.String<br />The AppUserModelID to assign to the current process.</dd></dl>

#### Return Value
Type: Int32<br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd378422%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd378422%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />