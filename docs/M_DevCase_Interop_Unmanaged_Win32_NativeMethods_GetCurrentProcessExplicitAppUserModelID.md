# NativeMethods.GetCurrentProcessExplicitAppUserModelID Method 
 

Retrieves the application-defined, explicit Application User Model ID (AppUserModelID) for the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll")]
public static int GetCurrentProcessExplicitAppUserModelID(
	out string refAppID
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll">]
Public Shared Function GetCurrentProcessExplicitAppUserModelID ( 
	<OutAttribute> ByRef refAppID As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim refAppID As String
Dim returnValue As Integer

returnValue = NativeMethods.GetCurrentProcessExplicitAppUserModelID(refAppID)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll")]
static int GetCurrentProcessExplicitAppUserModelID(
	[OutAttribute] String^% refAppID
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll")>]
static member GetCurrentProcessExplicitAppUserModelID : 
        refAppID : string byref -> int 

```


#### Parameters
&nbsp;<dl><dt>refAppID</dt><dd>Type: System.String<br />A pointer that receives the address of the AppUserModelID assigned to the process. 

 The caller is responsible for freeing this string with CoTaskMemFree when it is no longer needed.</dd></dl>

#### Return Value
Type: Int32<br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd378419%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd378419%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />