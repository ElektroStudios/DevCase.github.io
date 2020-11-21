# NativeMethods.NtOpenEvent Method (IntPtr, UInt32, ObjectAttributes)
 

Opens a handle to an existing named event object with the specified desired access.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll")]
public static NTStatus NtOpenEvent(
	out IntPtr refEventHandle,
	uint desiredAccess,
	in ObjectAttributes refObjectAttributes
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll">]
Public Shared Function NtOpenEvent ( 
	<OutAttribute> ByRef refEventHandle As IntPtr,
	desiredAccess As UInteger,
	ByRef refObjectAttributes As ObjectAttributes
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim refEventHandle As IntPtr
Dim desiredAccess As UInteger
Dim refObjectAttributes As ObjectAttributes
Dim returnValue As NTStatus

returnValue = NativeMethods.NtOpenEvent(refEventHandle, 
	desiredAccess, refObjectAttributes)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll")]
static NTStatus NtOpenEvent(
	[OutAttribute] IntPtr% refEventHandle, 
	[InAttribute] unsigned int desiredAccess, 
	[InAttribute] ObjectAttributes% refObjectAttributes
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll")>]
static member NtOpenEvent : 
        refEventHandle : IntPtr byref * 
        desiredAccess : uint32 * 
        refObjectAttributes : ObjectAttributes byref -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>refEventHandle</dt><dd>Type: System.IntPtr<br />A pointer to a variable that will receive the event object handle. 

 The handle includes bookkeeping information, such as a reference count and security context.</dd><dt>desiredAccess</dt><dd>Type: System.UInt32<br />The access mask value that represents the desired types of access for the event object.</dd><dt>refObjectAttributes</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">DevCase.Interop.Unmanaged.Win32.Structures.ObjectAttributes</a><br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes</a> structure that the caller supplied to be used for the specified object. 

 These attributes would include the ObjectName and the handle attributes, for example. This parameter is initialized by calling the InitializeObjectAttributes macro.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success, or the appropriate <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-zwopenevent" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-zwopenevent</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtOpenEvent">NtOpenEvent Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />