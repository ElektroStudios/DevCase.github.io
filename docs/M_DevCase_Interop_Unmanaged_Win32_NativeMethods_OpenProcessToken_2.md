# NativeMethods.OpenProcessToken Method (SafeHandle, TokenAccess, IntPtr)
 

Opens the access token associated with a process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static bool OpenProcessToken(
	SafeHandle processHandle,
	TokenAccess desiredAccess,
	ref IntPtr refTokenHandle
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function OpenProcessToken ( 
	processHandle As SafeHandle,
	desiredAccess As TokenAccess,
	ByRef refTokenHandle As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim processHandle As SafeHandle
Dim desiredAccess As TokenAccess
Dim refTokenHandle As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.OpenProcessToken(processHandle, 
	desiredAccess, refTokenHandle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static bool OpenProcessToken(
	SafeHandle^ processHandle, 
	TokenAccess desiredAccess, 
	IntPtr% refTokenHandle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member OpenProcessToken : 
        processHandle : SafeHandle * 
        desiredAccess : TokenAccess * 
        refTokenHandle : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>processHandle</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />An IntPtr handle to the process whose access token is opened. 

 The process must have the `PROCESS_QUERY_INFORMATION` access permission.</dd><dt>desiredAccess</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess</a><br />Specifies an access mask that specifies the requested types of access to the access token. 

 These requested access types are compared with the discretionary access control list (DACL) of the token to determine which accesses are granted or denied.</dd><dt>refTokenHandle</dt><dd>Type: System.IntPtr<br />Am IntPtr handle that identifies the newly opened access token when the function returns.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa379295%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa379295%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenProcessToken">OpenProcessToken Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />