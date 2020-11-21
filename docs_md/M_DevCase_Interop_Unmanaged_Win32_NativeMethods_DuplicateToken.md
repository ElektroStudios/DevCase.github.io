# NativeMethods.DuplicateToken Method 
 

Creates a new access token that duplicates one already in existence.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", SetLastError = true)]
public static bool DuplicateToken(
	IntPtr tokenHandle,
	SecurityImpersonationLevel impersonationLevel,
	ref IntPtr refDuplicateTokenHandle
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", SetLastError := true>]
Public Shared Function DuplicateToken ( 
	tokenHandle As IntPtr,
	impersonationLevel As SecurityImpersonationLevel,
	ByRef refDuplicateTokenHandle As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim tokenHandle As IntPtr
Dim impersonationLevel As SecurityImpersonationLevel
Dim refDuplicateTokenHandle As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.DuplicateToken(tokenHandle, 
	impersonationLevel, refDuplicateTokenHandle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", SetLastError = true)]
static bool DuplicateToken(
	IntPtr tokenHandle, 
	SecurityImpersonationLevel impersonationLevel, 
	IntPtr% refDuplicateTokenHandle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", SetLastError = true)>]
static member DuplicateToken : 
        tokenHandle : IntPtr * 
        impersonationLevel : SecurityImpersonationLevel * 
        refDuplicateTokenHandle : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>tokenHandle</dt><dd>Type: System.IntPtr<br />A handle to an access token opened with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Duplicate</a> access.</dd><dt>impersonationLevel</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SecurityImpersonationLevel">DevCase.Interop.Unmanaged.Win32.Enums.SecurityImpersonationLevel</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SecurityImpersonationLevel">SecurityImpersonationLevel</a> enumerated type that supplies the impersonation level of the new token.</dd><dt>refDuplicateTokenHandle</dt><dd>Type: System.IntPtr<br />A pointer to a variable that receives a handle to the duplicate token. 

 This handle has <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Impersonate</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Query</a> access to the new token. 

 When you have finished using the new token, call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CloseHandle">CloseHandle(IntPtr)</a> function to close the token handle.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 



## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa446616%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa446616%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />