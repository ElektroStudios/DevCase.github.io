# NativeMethods.OpenThreadToken Method (SafeHandle, TokenAccess, Boolean, IntPtr)
 

Opens the access token associated with a thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static bool OpenThreadToken(
	SafeHandle threadHandle,
	TokenAccess desiredAccess,
	bool openAsSelf,
	ref IntPtr refTokenHandle
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function OpenThreadToken ( 
	threadHandle As SafeHandle,
	desiredAccess As TokenAccess,
	openAsSelf As Boolean,
	ByRef refTokenHandle As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim threadHandle As SafeHandle
Dim desiredAccess As TokenAccess
Dim openAsSelf As Boolean
Dim refTokenHandle As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.OpenThreadToken(threadHandle, 
	desiredAccess, openAsSelf, refTokenHandle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static bool OpenThreadToken(
	SafeHandle^ threadHandle, 
	TokenAccess desiredAccess, 
	bool openAsSelf, 
	IntPtr% refTokenHandle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member OpenThreadToken : 
        threadHandle : SafeHandle * 
        desiredAccess : TokenAccess * 
        openAsSelf : bool * 
        refTokenHandle : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>threadHandle</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle To the thread whose access token Is opened.</dd><dt>desiredAccess</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">DevCase.Interop.Unmanaged.Win32.Enums.TokenAccess</a><br />Specifies an access mask that specifies the requested types of access to the access token. 

 These requested access types are compared with the discretionary access control list (DACL) of the token to determine which accesses are granted or denied.</dd><dt>openAsSelf</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) if the access check is to be made against the process-level security context. 

`false` (`False` in Visual Basic) if the access check is to be made against the current security context of the thread calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenThreadToken">OpenThreadToken(IntPtr, TokenAccess, Boolean, IntPtr)</a> function. 

 The *openAsSelf* parameter allows the caller of this function to open the access token of a specified thread when the caller is impersonating a token at SecurityIdentification level. Without this parameter, the calling thread cannot open the access token on the specified thread because it is impossible to open executive-level objects by using the SecurityIdentification impersonation level.</dd><dt>refTokenHandle</dt><dd>Type: System.IntPtr<br />A IntPtr handle that identifies the newly opened access token when the function returns.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa379296%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa379296%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenThreadToken">OpenThreadToken Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />