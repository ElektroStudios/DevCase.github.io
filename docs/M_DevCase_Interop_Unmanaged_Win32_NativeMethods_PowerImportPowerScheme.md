# NativeMethods.PowerImportPowerScheme Method 
 

Imports a power scheme from a file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PowrProf.dll", CharSet = CharSet.Unicode)]
public static Win32ErrorCode PowerImportPowerScheme(
	IntPtr rootPowerKey,
	string filepath,
	ref Guid refDstSchemeGuid
)
```

**VB**<br />
``` VB
<DllImportAttribute("PowrProf.dll", CharSet := CharSet.Unicode>]
Public Shared Function PowerImportPowerScheme ( 
	rootPowerKey As IntPtr,
	filepath As String,
	ByRef refDstSchemeGuid As Guid
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim rootPowerKey As IntPtr
Dim filepath As String
Dim refDstSchemeGuid As Guid
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.PowerImportPowerScheme(rootPowerKey, 
	filepath, refDstSchemeGuid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PowrProf.dll", CharSet = CharSet::Unicode)]
static Win32ErrorCode PowerImportPowerScheme(
	IntPtr rootPowerKey, 
	String^ filepath, 
	Guid% refDstSchemeGuid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PowrProf.dll", CharSet = CharSet.Unicode)>]
static member PowerImportPowerScheme : 
        rootPowerKey : IntPtr * 
        filepath : string * 
        refDstSchemeGuid : Guid byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>rootPowerKey</dt><dd>Type: System.IntPtr<br />Reserved for future use, this must be set to Zero.</dd><dt>filepath</dt><dd>Type: System.String<br />The path to a power scheme backup file created by `PowerCfg.Exe /Export`.</dd><dt>refDstSchemeGuid</dt><dd>Type: System.Guid<br />Returns a Guid referring to the power scheme.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> (zero) if the call was successful, and a nonzero value if the call failed.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa372732%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa372732%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />