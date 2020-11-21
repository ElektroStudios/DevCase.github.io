# NativeMethods.NtOpenSection Method (IntPtr, StandardAccessRights, IntPtr)
 

Opens a handle for an existing section object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", CallingConvention = CallingConvention.StdCall)]
public static NTStatus NtOpenSection(
	out IntPtr refSection,
	StandardAccessRights desiredAccess,
	in IntPtr refObjectAttributes
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", CallingConvention := CallingConvention.StdCall>]
Public Shared Function NtOpenSection ( 
	<OutAttribute> ByRef refSection As IntPtr,
	desiredAccess As StandardAccessRights,
	ByRef refObjectAttributes As IntPtr
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim refSection As IntPtr
Dim desiredAccess As StandardAccessRights
Dim refObjectAttributes As IntPtr
Dim returnValue As NTStatus

returnValue = NativeMethods.NtOpenSection(refSection, 
	desiredAccess, refObjectAttributes)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", CallingConvention = CallingConvention::StdCall)]
static NTStatus NtOpenSection(
	[OutAttribute] IntPtr% refSection, 
	[InAttribute] StandardAccessRights desiredAccess, 
	[InAttribute] IntPtr% refObjectAttributes
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", CallingConvention = CallingConvention.StdCall)>]
static member NtOpenSection : 
        refSection : IntPtr byref * 
        desiredAccess : StandardAccessRights * 
        refObjectAttributes : IntPtr byref -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>refSection</dt><dd>Type: System.IntPtr<br />Handle to a section object.</dd><dt>desiredAccess</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">DevCase.Interop.Unmanaged.Win32.Enums.StandardAccessRights</a><br />The requested access to the object.</dd><dt>refObjectAttributes</dt><dd>Type: System.IntPtr<br />Pointer to an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes</a> structure that specifies the object name and other attributes. 

 Use InitializeObjectAttributes to initialize this structure. 

 If the caller is not running in a system thread context, it must set the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ObjectHandleAttributes">KernelHandle</a> attribute when it calls InitializeObjectAttributes.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success, or the appropriate <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-zwopensection" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-zwopensection</a><a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/section-objects-and-views" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/section-objects-and-views</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtOpenSection">NtOpenSection Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />