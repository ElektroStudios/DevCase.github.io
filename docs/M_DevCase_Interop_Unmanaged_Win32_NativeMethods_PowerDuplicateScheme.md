# NativeMethods.PowerDuplicateScheme Method 
 

Duplicates an existing power scheme.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PowrProf.dll")]
public static Win32ErrorCode PowerDuplicateScheme(
	IntPtr rootPowerKey,
	ref Guid refSrcSchemeGuid,
	ref IntPtr refDstSchemeGuid
)
```

**VB**<br />
``` VB
<DllImportAttribute("PowrProf.dll">]
Public Shared Function PowerDuplicateScheme ( 
	rootPowerKey As IntPtr,
	ByRef refSrcSchemeGuid As Guid,
	ByRef refDstSchemeGuid As IntPtr
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim rootPowerKey As IntPtr
Dim refSrcSchemeGuid As Guid
Dim refDstSchemeGuid As IntPtr
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.PowerDuplicateScheme(rootPowerKey, 
	refSrcSchemeGuid, refDstSchemeGuid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PowrProf.dll")]
static Win32ErrorCode PowerDuplicateScheme(
	IntPtr rootPowerKey, 
	Guid% refSrcSchemeGuid, 
	IntPtr% refDstSchemeGuid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PowrProf.dll")>]
static member PowerDuplicateScheme : 
        rootPowerKey : IntPtr * 
        refSrcSchemeGuid : Guid byref * 
        refDstSchemeGuid : IntPtr byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>rootPowerKey</dt><dd>Type: System.IntPtr<br />Reserved for future use, this must be set to Zero.</dd><dt>refSrcSchemeGuid</dt><dd>Type: System.Guid<br />The Guid referring to the power scheme that is to be duplicated.</dd><dt>refDstSchemeGuid</dt><dd>Type: System.IntPtr<br />The emptyness Guid that will receive the duplicate.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> (zero) if the call was successful, and a nonzero value if the call failed.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa372729%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa372729%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />