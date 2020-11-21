# NativeMethods.LookupPrivilegeName Method 
 

Retrieves the name that corresponds to the privilege represented on a specific system by a specified locally unique identifier (LUID).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool LookupPrivilegeName(
	string systemName,
	ref Luid refLuid,
	StringBuilder name,
	ref int refCchName
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function LookupPrivilegeName ( 
	systemName As String,
	ByRef refLuid As Luid,
	name As StringBuilder,
	ByRef refCchName As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim systemName As String
Dim refLuid As Luid
Dim name As StringBuilder
Dim refCchName As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.LookupPrivilegeName(systemName, 
	refLuid, name, refCchName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool LookupPrivilegeName(
	String^ systemName, 
	Luid% refLuid, 
	StringBuilder^ name, 
	int% refCchName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member LookupPrivilegeName : 
        systemName : string * 
        refLuid : Luid byref * 
        name : StringBuilder * 
        refCchName : int byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>systemName</dt><dd>Type: System.String<br />A pointer to a null-terminated string that specifies the name of the system on which the privilege name is retrieved. 

 If a empty string is specified, the function attempts to find the privilege name on the local system.</dd><dt>refLuid</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Luid">DevCase.Interop.Unmanaged.Win32.Structures.Luid</a><br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Luid">Luid</a> structure by which the privilege is known on the target system.</dd><dt>name</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives a null-terminated string that represents the privilege name. 

 For example, this string could be "`SeSecurityPrivilege`".</dd><dt>refCchName</dt><dd>Type: System.Int32<br />A pointer to a variable that specifies the size, in a TCHAR value, of the lpName buffer. 

 When the function returns, this parameter contains the length of the privilege name, not including the terminating null character. 

 If the buffer pointed to by the *name* parameter is too small, this variable contains the required size.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is a `true` (`True` in Visual Basic). 

 If the function succeeds, the return value is a `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa379176%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa379176%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />