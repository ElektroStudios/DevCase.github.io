# NativeMethods.UnloadUserProfile Method 
 

Unloads a user's profile that was loaded by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadUserProfile">LoadUserProfile(IntPtr, UserProfileInfo)</a> function. 

 The caller must have administrative privileges to unload a user's profile.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("UserEnv.dll", EntryPoint = "LoadUserProfile", CharSet = CharSet.Auto, 
	SetLastError = true)]
public static bool UnloadUserProfile(
	IntPtr hToken,
	IntPtr hProfile
)
```

**VB**<br />
``` VB
<DllImportAttribute("UserEnv.dll", EntryPoint := "LoadUserProfile", CharSet := CharSet.Auto, 
	SetLastError := true>]
Public Shared Function UnloadUserProfile ( 
	hToken As IntPtr,
	hProfile As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hToken As IntPtr
Dim hProfile As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.UnloadUserProfile(hToken, 
	hProfile)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"UserEnv.dll", EntryPoint = L"LoadUserProfile", 
	CharSet = CharSet::Auto, SetLastError = true)]
static bool UnloadUserProfile(
	IntPtr hToken, 
	IntPtr hProfile
)
```

**F#**<br />
``` F#
[<DllImportAttribute("UserEnv.dll", EntryPoint = "LoadUserProfile", CharSet = CharSet.Auto, 
	SetLastError = true)>]
static member UnloadUserProfile : 
        hToken : IntPtr * 
        hProfile : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hToken</dt><dd>Type: System.IntPtr<br />Token for the user, which is returned by the LogonUser, CreateRestrictedToken, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DuplicateToken">DuplicateToken(IntPtr, SecurityImpersonationLevel, IntPtr)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenProcessToken">OpenProcessToken(SafeProcessHandle, TokenAccess, IntPtr)</a>, or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenThreadToken">OpenThreadToken(IntPtr, TokenAccess, Boolean, IntPtr)</a> function. 

 The token must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Impersonate</a>, and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Duplicate</a> access.</dd><dt>hProfile</dt><dd>Type: System.IntPtr<br />Handle to the registry key. 

 This value is the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_RegistryHandle">RegistryHandle</a> member.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762282%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762282%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />