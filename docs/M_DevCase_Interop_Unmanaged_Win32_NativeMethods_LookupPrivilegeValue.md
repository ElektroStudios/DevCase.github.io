# NativeMethods.LookupPrivilegeValue Method 
 

Retrieves the locally unique identifier (LUID) used on a specified system, to locally represent the specified privilege name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool LookupPrivilegeValue(
	string systemName,
	string name,
	ref Luid refLuid
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function LookupPrivilegeValue ( 
	systemName As String,
	name As String,
	ByRef refLuid As Luid
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim systemName As String
Dim name As String
Dim refLuid As Luid
Dim returnValue As Boolean

returnValue = NativeMethods.LookupPrivilegeValue(systemName, 
	name, refLuid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool LookupPrivilegeValue(
	String^ systemName, 
	String^ name, 
	Luid% refLuid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member LookupPrivilegeValue : 
        systemName : string * 
        name : string * 
        refLuid : Luid byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>systemName</dt><dd>Type: System.String<br />A pointer to a null-terminated string that specifies the name of the system on which the privilege name is retrieved. 

 If a null string is specified, the function attempts to find the privilege name on the local system</dd><dt>name</dt><dd>Type: System.String<br />A pointer to a null-terminated string that specifies the name of the privilege, as defined in the `Winnt.h` header file. 

 For example, this parameter could specify the constant, `SE_SECURITY_NAME`, or its corresponding string, "SeSecurityPrivilege".</dd><dt>refLuid</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Luid">DevCase.Interop.Unmanaged.Win32.Structures.Luid</a><br />A pointer to a variable that receives the LUID by which the privilege is known on the system specified by the *systemName* parameter.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the function returns `true` (`True` in Visual Basic). 

 If the function fails, it returns `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa379180%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa379180%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />