# NativeMethods.CreateProfile Method 
 

Creates a new user profile. 

 The caller must have administrative privileges to create a user's profile.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("UserEnv.dll", CharSet = CharSet.Auto, ThrowOnUnmappableChar = true, 
	SetLastError = true)]
public static int CreateProfile(
	string userSid,
	string userName,
	StringBuilder profilePath,
	uint bufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("UserEnv.dll", CharSet := CharSet.Auto, ThrowOnUnmappableChar := true, 
	SetLastError := true>]
Public Shared Function CreateProfile ( 
	userSid As String,
	userName As String,
	<OutAttribute> profilePath As StringBuilder,
	bufferSize As UInteger
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim userSid As String
Dim userName As String
Dim profilePath As StringBuilder
Dim bufferSize As UInteger
Dim returnValue As Integer

returnValue = NativeMethods.CreateProfile(userSid, 
	userName, profilePath, bufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"UserEnv.dll", CharSet = CharSet::Auto, ThrowOnUnmappableChar = true, 
	SetLastError = true)]
static int CreateProfile(
	String^ userSid, 
	String^ userName, 
	[OutAttribute] StringBuilder^ profilePath, 
	unsigned int bufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("UserEnv.dll", CharSet = CharSet.Auto, ThrowOnUnmappableChar = true, 
	SetLastError = true)>]
static member CreateProfile : 
        userSid : string * 
        userName : string * 
        profilePath : StringBuilder byref * 
        bufferSize : uint32 -> int 

```


#### Parameters
&nbsp;<dl><dt>userSid</dt><dd>Type: System.String<br />Pointer to the `SID` of the user as a string.</dd><dt>userName</dt><dd>Type: System.String<br />The user name of the new user. 

 This name is used as the base name for the profile directory.</dd><dt>profilePath</dt><dd>Type: System.Text.StringBuilder<br />When this function returns, contains a pointer to the full path of the profile.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />Size of the buffer pointed to by *profilePath* parameter, in characters.</dd></dl>

#### Return Value
Type: Int32<br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if successful, otherwise, an `HRESULT` error value.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762271%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762271%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />