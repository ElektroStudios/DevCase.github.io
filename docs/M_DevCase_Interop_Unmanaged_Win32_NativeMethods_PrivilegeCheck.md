# NativeMethods.PrivilegeCheck Method 
 

Determines whether a specified set of privileges are enabled in an access token. 

 This function is typically called by a server application to check the privileges of a client's access token.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static bool PrivilegeCheck(
	IntPtr token,
	out PrivilegeSet refPrivileges,
	ref bool refResult
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function PrivilegeCheck ( 
	token As IntPtr,
	<OutAttribute> ByRef refPrivileges As PrivilegeSet,
	ByRef refResult As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim token As IntPtr
Dim refPrivileges As PrivilegeSet
Dim refResult As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.PrivilegeCheck(token, 
	refPrivileges, refResult)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static bool PrivilegeCheck(
	IntPtr token, 
	[InAttribute] [OutAttribute] PrivilegeSet% refPrivileges, 
	bool% refResult
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member PrivilegeCheck : 
        token : IntPtr * 
        refPrivileges : PrivilegeSet byref * 
        refResult : bool byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>token</dt><dd>Type: System.IntPtr<br />A handle to an access token representing a client process. 

 This handle must have been obtained by opening the token of a thread impersonating the client. 

 The token must be open for <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Query</a> access.</dd><dt>refPrivileges</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet">DevCase.Interop.Unmanaged.Win32.Structures.PrivilegeSet</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet">PrivilegeSet</a> structure. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet_Privileges">Privileges</a> member of this structure is an array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_LuidAndAttributes">LuidAndAttributes</a> structures. 

 Before calling `PrivilegeCheck`, use the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet_Privileges">Privileges</a> array to indicate the set of privileges to check. 

 Set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet_Control">Control</a> member to `PRIVILEGE_SET_ALL_NECESSARY` if all of the privileges must be enabled; or set it to `0` if it is sufficient that any one of the privileges be enabled. 



 When `PrivilegeCheck` returns, the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_LuidAndAttributes_Attributes">Attributes</a> member of each <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_LuidAndAttributes">LuidAndAttributes</a> structure is set to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PrivilegeStates">PrivilegeUsedForAccess</a> if the corresponding privilege is enabled.</dd><dt>refResult</dt><dd>Type: System.Boolean<br />A pointer to a value the function sets to indicate whether any or all of the specified privileges are enabled in the access token. 

 If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet_Control">Control</a> member of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet">PrivilegeSet</a> structure specifies `PRIVILEGE_SET_ALL_NECESSARY`, this value is `true` (`True` in Visual Basic) only if all the privileges are enabled; otherwise, this value is `true` (`True` in Visual Basic) if any of the privileges are enabled.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 



## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa379304%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa379304%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />