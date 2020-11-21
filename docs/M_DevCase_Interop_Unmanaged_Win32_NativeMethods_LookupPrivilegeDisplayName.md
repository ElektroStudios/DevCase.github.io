# NativeMethods.LookupPrivilegeDisplayName Method 
 

Retrieves the display name that represents a specified privilege.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool LookupPrivilegeDisplayName(
	string systemName,
	string name,
	StringBuilder displayName,
	ref uint refDisplayNameSize,
	out uint refLanguageId
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function LookupPrivilegeDisplayName ( 
	systemName As String,
	name As String,
	displayName As StringBuilder,
	ByRef refDisplayNameSize As UInteger,
	<OutAttribute> ByRef refLanguageId As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim systemName As String
Dim name As String
Dim displayName As StringBuilder
Dim refDisplayNameSize As UInteger
Dim refLanguageId As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.LookupPrivilegeDisplayName(systemName, 
	name, displayName, refDisplayNameSize, 
	refLanguageId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool LookupPrivilegeDisplayName(
	String^ systemName, 
	String^ name, 
	StringBuilder^ displayName, 
	unsigned int% refDisplayNameSize, 
	[OutAttribute] unsigned int% refLanguageId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member LookupPrivilegeDisplayName : 
        systemName : string * 
        name : string * 
        displayName : StringBuilder * 
        refDisplayNameSize : uint32 byref * 
        refLanguageId : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>systemName</dt><dd>Type: System.String<br />A pointer to a null-terminated string that specifies the name of the system on which the privilege name is retrieved. 

 If a null string is specified, the function attempts to find the display name on the local system.</dd><dt>name</dt><dd>Type: System.String<br />A pointer to a null-terminated string that specifies the name of the privilege, as defined in Winnt.h. 

 For example, this parameter could specify the constant, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">RemoteShutdownPrivilege</a>, or its corresponding string, "SeRemoteShutdownPrivilege".</dd><dt>displayName</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives a null-terminated string that specifies the privilege display name. 

 For example, if the *name* parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">RemoteShutdownPrivilege</a>, the privilege display name is "Force shutdown from a remote system.".</dd><dt>refDisplayNameSize</dt><dd>Type: System.UInt32<br />A pointer to a variable that specifies the size, in characters, of the *displayName* buffer. 

 When the function returns, this parameter contains the length of the privilege display name, not including the terminating null character. 

 If the buffer pointed to by the *displayName* parameter is too small, this variable contains the required size.</dd><dt>refLanguageId</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the language identifier for the returned display name.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-lookupprivilegedisplaynamea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-lookupprivilegedisplaynamea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />