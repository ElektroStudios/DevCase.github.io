# NativeMethods.NtExtendSection Method 
 

Extends the size of an existing section object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", CallingConvention = CallingConvention.StdCall)]
public static NTStatus NtExtendSection(
	IntPtr hSection,
	ulong newSectionSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", CallingConvention := CallingConvention.StdCall>]
Public Shared Function NtExtendSection ( 
	hSection As IntPtr,
	newSectionSize As ULong
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim hSection As IntPtr
Dim newSectionSize As ULong
Dim returnValue As NTStatus

returnValue = NativeMethods.NtExtendSection(hSection, 
	newSectionSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", CallingConvention = CallingConvention::StdCall)]
static NTStatus NtExtendSection(
	IntPtr hSection, 
	unsigned long long newSectionSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", CallingConvention = CallingConvention.StdCall)>]
static member NtExtendSection : 
        hSection : IntPtr * 
        newSectionSize : uint64 -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>hSection</dt><dd>Type: System.IntPtr<br />Handle to a section object. 

 The handle must be open with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SectionAccessRights">ExtendSize</a> right. 

 If section points to a mapped file, NtExtendSection(IntPtr, UInt64) fails.</dd><dt>newSectionSize</dt><dd>Type: System.UInt64<br />The new size for the section object.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success, or the appropriate <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> error code on failure.

## Remarks
<a href="http://undocumented.ntinternals.net/UserMode/Undocumented%20Functions/NT%20Objects/Section/NtExtendSection.html" target="_blank">http://undocumented.ntinternals.net/UserMode/Undocumented%20Functions/NT%20Objects/Section/NtExtendSection.html</a><a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/section-objects-and-views" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/section-objects-and-views</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />