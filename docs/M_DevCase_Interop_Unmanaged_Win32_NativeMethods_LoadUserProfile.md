# NativeMethods.LoadUserProfile Method 
 

Loads the specified user's profile. The profile can be a local user profile or a roaming user profile. 

 The caller must have administrative privileges to load a user's profile.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("UserEnv.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static bool LoadUserProfile(
	IntPtr hToken,
	ref UserProfileInfo refProfileInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("UserEnv.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function LoadUserProfile ( 
	hToken As IntPtr,
	ByRef refProfileInfo As UserProfileInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hToken As IntPtr
Dim refProfileInfo As UserProfileInfo
Dim returnValue As Boolean

returnValue = NativeMethods.LoadUserProfile(hToken, 
	refProfileInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"UserEnv.dll", CharSet = CharSet::Auto, SetLastError = true)]
static bool LoadUserProfile(
	IntPtr hToken, 
	UserProfileInfo% refProfileInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("UserEnv.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member LoadUserProfile : 
        hToken : IntPtr * 
        refProfileInfo : UserProfileInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hToken</dt><dd>Type: System.IntPtr<br />Token for the user, which is returned by the LogonUser, CreateRestrictedToken, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DuplicateToken">DuplicateToken(IntPtr, SecurityImpersonationLevel, IntPtr)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenProcessToken">OpenProcessToken(SafeProcessHandle, TokenAccess, IntPtr)</a>, or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenThreadToken">OpenThreadToken(IntPtr, TokenAccess, Boolean, IntPtr)</a> function. 

 The token must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Query</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Impersonate</a>, and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Duplicate</a> access.</dd><dt>refProfileInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo">DevCase.Interop.Unmanaged.Win32.Structures.UserProfileInfo</a><br />Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo">UserProfileInfo</a> structure. 

 The function LoadUserProfile(IntPtr, UserProfileInfo) fails and returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_INVALIDARG</a> if the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_SizeOfStruct">SizeOfStruct</a> member is not set to `Marshal.SizeOf(Of UserProfileInfo)` or if the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_UserName">UserName</a> member is a null reference (`Nothing` in Visual Basic). 

 If this parameter is a null reference (`Nothing` in Visual Basic), the function obtains the path from the registry.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762281%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762281%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />