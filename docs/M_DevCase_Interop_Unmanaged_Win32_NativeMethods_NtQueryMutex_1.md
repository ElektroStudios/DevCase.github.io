# NativeMethods.NtQueryMutex Method (IntPtr, MutexInformationClass, MutexOwnerInformation, Int32, Int32)
 

Queries a mutual exclusion (Mutex) object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", EntryPoint = "NtQueryMutant")]
public static NTStatus NtQueryMutex(
	IntPtr mutexHandle,
	MutexInformationClass mutexInformationClass,
	out MutexOwnerInformation refMutexInformation,
	int mutexInformationLength,
	[OptionalAttribute] out int refReturnLength
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", EntryPoint := "NtQueryMutant">]
Public Shared Function NtQueryMutex ( 
	mutexHandle As IntPtr,
	mutexInformationClass As MutexInformationClass,
	<OutAttribute> ByRef refMutexInformation As MutexOwnerInformation,
	mutexInformationLength As Integer,
	<OptionalAttribute> <OutAttribute> ByRef refReturnLength As Integer
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim mutexHandle As IntPtr
Dim mutexInformationClass As MutexInformationClass
Dim refMutexInformation As MutexOwnerInformation
Dim mutexInformationLength As Integer
Dim refReturnLength As Integer
Dim returnValue As NTStatus

returnValue = NativeMethods.NtQueryMutex(mutexHandle, 
	mutexInformationClass, refMutexInformation, 
	mutexInformationLength, refReturnLength)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", EntryPoint = L"NtQueryMutant")]
static NTStatus NtQueryMutex(
	[InAttribute] IntPtr mutexHandle, 
	[InAttribute] MutexInformationClass mutexInformationClass, 
	[OutAttribute] MutexOwnerInformation% refMutexInformation, 
	[InAttribute] int mutexInformationLength, 
	[OptionalAttribute] [OutAttribute] int% refReturnLength
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", EntryPoint = "NtQueryMutant")>]
static member NtQueryMutex : 
        mutexHandle : IntPtr * 
        mutexInformationClass : MutexInformationClass * 
        refMutexInformation : MutexOwnerInformation byref * 
        mutexInformationLength : int * 
        [<OptionalAttribute>] refReturnLength : int byref -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>mutexHandle</dt><dd>Type: System.IntPtr<br />The Mutex handle.</dd><dt>mutexInformationClass</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MutexInformationClass">DevCase.Interop.Unmanaged.Win32.Enums.MutexInformationClass</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MutexInformationClass">MutexInformationClass</a>.</dd><dt>refMutexInformation</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MutexOwnerInformation">DevCase.Interop.Unmanaged.Win32.Structures.MutexOwnerInformation</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MutexOwnerInformation">MutexOwnerInformation</a>.</dd><dt>mutexInformationLength</dt><dd>Type: System.Int32<br />Length of the Mutex information.</dd><dt>refReturnLength (Optional)</dt><dd>Type: System.Int32<br />Length of the return value.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success, or the appropriate <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> error code on failure.

## Remarks
<a href="https://undocumented.ntinternals.net/index.html?page=UserMode%2FUndocumented%20Functions%2FNT%20Objects%2FMutant%2FNtQueryMutant.html" target="_blank">https://undocumented.ntinternals.net/index.html?page=UserMode%2FUndocumented%20Functions%2FNT%20Objects%2FMutant%2FNtQueryMutant.html</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtQueryMutex">NtQueryMutex Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />