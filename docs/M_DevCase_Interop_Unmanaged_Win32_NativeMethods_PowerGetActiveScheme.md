# NativeMethods.PowerGetActiveScheme Method 
 

Retrieves the active power scheme and returns a GUID that identifies the scheme.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PowrProf.dll")]
public static Win32ErrorCode PowerGetActiveScheme(
	[OptionalAttribute] IntPtr rootPowerKey,
	ref Guid refSchemeGuid
)
```

**VB**<br />
``` VB
<DllImportAttribute("PowrProf.dll">]
Public Shared Function PowerGetActiveScheme ( 
	<OptionalAttribute> rootPowerKey As IntPtr,
	ByRef refSchemeGuid As Guid
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim rootPowerKey As IntPtr
Dim refSchemeGuid As Guid
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.PowerGetActiveScheme(rootPowerKey, 
	refSchemeGuid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PowrProf.dll")]
static Win32ErrorCode PowerGetActiveScheme(
	[OptionalAttribute] IntPtr rootPowerKey, 
	Guid% refSchemeGuid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PowrProf.dll")>]
static member PowerGetActiveScheme : 
        [<OptionalAttribute>] rootPowerKey : IntPtr * 
        refSchemeGuid : Guid byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>rootPowerKey (Optional)</dt><dd>Type: System.IntPtr<br />Reserved for future use, this must be set to Zero.</dd><dt>refSchemeGuid</dt><dd>Type: System.Guid<br />Returns a Guid referring to the currently active power scheme.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> (zero) if the call was successful, and a nonzero value if the call failed.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa372731%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa372731%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />