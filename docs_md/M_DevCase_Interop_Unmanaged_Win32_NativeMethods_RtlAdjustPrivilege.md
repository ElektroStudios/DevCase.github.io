# NativeMethods.RtlAdjustPrivilege Method 
 

Enables or disables a privilege from the calling thread or process. 

 Enabling or disabling privileges requires <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">AdjustPrivileges</a> access.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", SetLastError = true)]
public static uint RtlAdjustPrivilege(
	int privileges,
	bool enablePrivilege,
	bool isThreadPrivilege,
	ref bool refPreviousValue
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", SetLastError := true>]
Public Shared Function RtlAdjustPrivilege ( 
	privileges As Integer,
	enablePrivilege As Boolean,
	isThreadPrivilege As Boolean,
	ByRef refPreviousValue As Boolean
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim privileges As Integer
Dim enablePrivilege As Boolean
Dim isThreadPrivilege As Boolean
Dim refPreviousValue As Boolean
Dim returnValue As UInteger

returnValue = NativeMethods.RtlAdjustPrivilege(privileges, 
	enablePrivilege, isThreadPrivilege, 
	refPreviousValue)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", SetLastError = true)]
static unsigned int RtlAdjustPrivilege(
	int privileges, 
	bool enablePrivilege, 
	bool isThreadPrivilege, 
	bool% refPreviousValue
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", SetLastError = true)>]
static member RtlAdjustPrivilege : 
        privileges : int * 
        enablePrivilege : bool * 
        isThreadPrivilege : bool * 
        refPreviousValue : bool byref -> uint32 

```


#### Parameters
&nbsp;<dl><dt>privileges</dt><dd>Type: System.Int32<br />One or more privileges to set. 

 See: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">ProcessPrivileges</a></dd><dt>enablePrivilege</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), enable the privilege, otherwise, in the calling process.</dd><dt>isThreadPrivilege</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), the privilege is set for the calling thread, otherwise, for the calling process.</dd><dt>refPreviousValue</dt><dd>Type: System.Boolean<br />A value that indicates whether the privilege was previously enabled or disabled.</dd></dl>

#### Return Value
Type: UInt32<br />(Not documented)

## Remarks
<a href="https://source.winehq.org/WineAPI/RtlAdjustPrivilege.html" target="_blank">https://source.winehq.org/WineAPI/RtlAdjustPrivilege.html</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />