# NativeMethods.AdjustTokenPrivileges Method 
 

Enables or disables privileges in the specified access token. 

 Enabling or disabling privileges in an access token requires <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">AdjustPrivileges</a> access. 

 Note that AdjustTokenPrivileges(IntPtr, Boolean, TokenPrivileges, Int32, TokenPrivileges, IntPtr) cannot add or remove privileges from the token. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static bool AdjustTokenPrivileges(
	IntPtr tokenHandle,
	bool disableAllPrivileges,
	ref TokenPrivileges refNewState,
	int bufferLength,
	ref TokenPrivileges refPreviousState,
	ref IntPtr refReturnLength
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function AdjustTokenPrivileges ( 
	tokenHandle As IntPtr,
	disableAllPrivileges As Boolean,
	ByRef refNewState As TokenPrivileges,
	bufferLength As Integer,
	ByRef refPreviousState As TokenPrivileges,
	ByRef refReturnLength As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim tokenHandle As IntPtr
Dim disableAllPrivileges As Boolean
Dim refNewState As TokenPrivileges
Dim bufferLength As Integer
Dim refPreviousState As TokenPrivileges
Dim refReturnLength As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.AdjustTokenPrivileges(tokenHandle, 
	disableAllPrivileges, refNewState, 
	bufferLength, refPreviousState, 
	refReturnLength)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static bool AdjustTokenPrivileges(
	IntPtr tokenHandle, 
	bool disableAllPrivileges, 
	TokenPrivileges% refNewState, 
	int bufferLength, 
	TokenPrivileges% refPreviousState, 
	IntPtr% refReturnLength
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member AdjustTokenPrivileges : 
        tokenHandle : IntPtr * 
        disableAllPrivileges : bool * 
        refNewState : TokenPrivileges byref * 
        bufferLength : int * 
        refPreviousState : TokenPrivileges byref * 
        refReturnLength : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>tokenHandle</dt><dd>Type: System.IntPtr<br />An IntPtr pointer handle to the access token that contains the privileges to be modified. 

 The handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">AdjustPrivileges</a> access to the token. 

 If the *refPreviousState* parameter is not a null reference (`Nothing` in Visual Basic), the handle must also have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Query</a> access.</dd><dt>disableAllPrivileges</dt><dd>Type: System.Boolean<br />Specifies whether the function disables all of the token's privileges. 

 If this value is `true` (`True` in Visual Basic), the function disables all privileges and ignores the *refNewState* parameter. 

 If it is `false` (`False` in Visual Basic), the function modifies privileges based on the information pointed to by the *refNewState* parameter.</dd><dt>refNewState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges">DevCase.Interop.Unmanaged.Win32.Structures.TokenPrivileges</a><br />A IntPtr pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges">TokenPrivileges</a> structure that specifies an array of privileges and their attributes. 

 If the *disableAllPrivileges* parameter is `false` (`False` in Visual Basic), the AdjustTokenPrivileges(IntPtr, Boolean, TokenPrivileges, Int32, TokenPrivileges, IntPtr) function enables, disables, or removes these privileges for the token.</dd><dt>bufferLength</dt><dd>Type: System.Int32<br />Specifies the size, in bytes, of the buffer pointed to by the *refPreviousState* parameter. 

 This parameter can be zero if the *refPreviousState* parameter is a null reference (`Nothing` in Visual Basic).</dd><dt>refPreviousState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges">DevCase.Interop.Unmanaged.Win32.Structures.TokenPrivileges</a><br />A pointer to a buffer that the function fills with a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges">TokenPrivileges</a> structure that contains the previous state of any privileges that the function modifies. 

 That is, if a privilege has been modified by this function, the privilege and its previous state are contained in the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges">TokenPrivileges</a> structure referenced by *refPreviousState*. 

 If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges_PrivilegeCount">PrivilegeCount</a> member is `0`, then no privileges have been changed by this function. 

 This parameter can be a null reference (`Nothing` in Visual Basic).</dd><dt>refReturnLength</dt><dd>Type: System.IntPtr<br />A pointer to a variable that receives the required size, in bytes, of the buffer pointed to by the *refPreviousState* parameter. 

 This parameter can be a null reference (`Nothing` in Visual Basic) if *refPreviousState* is a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic), otherwise, `false` (`False` in Visual Basic). 

 To determine whether the function adjusted all of the specified privileges, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa375202%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa375202%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />