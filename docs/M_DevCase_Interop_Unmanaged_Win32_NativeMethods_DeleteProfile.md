# NativeMethods.DeleteProfile Method 
 

Deletes the user profile and all user-related settings from the specified computer. 

 The caller must have administrative privileges to delete a user's profile.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("UserEnv.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool DeleteProfile(
	string userSid,
	string profilePath,
	string computerName
)
```

**VB**<br />
``` VB
<DllImportAttribute("UserEnv.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function DeleteProfile ( 
	userSid As String,
	profilePath As String,
	computerName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim userSid As String
Dim profilePath As String
Dim computerName As String
Dim returnValue As Boolean

returnValue = NativeMethods.DeleteProfile(userSid, 
	profilePath, computerName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"UserEnv.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool DeleteProfile(
	String^ userSid, 
	String^ profilePath, 
	String^ computerName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("UserEnv.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member DeleteProfile : 
        userSid : string * 
        profilePath : string * 
        computerName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>userSid</dt><dd>Type: System.String<br />Pointer to the `SID` of the user as a string.</dd><dt>profilePath</dt><dd>Type: System.String<br />Pointer to a string that specifies the profile path. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the function obtains the path from the registry.</dd><dt>computerName</dt><dd>Type: System.String<br />Pointer to a string that specifies the name of the computer from which the profile is to be deleted. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the local computer name is used. 



 Note: As of Windows Vista, this parameter must be a null reference (`Nothing` in Visual Basic). If it is not, this function fails with the error code <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_INVALIDARG</a>.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762273%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762273%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />