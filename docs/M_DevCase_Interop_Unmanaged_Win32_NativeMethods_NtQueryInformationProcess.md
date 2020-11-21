# NativeMethods.NtQueryInformationProcess Method 
 

Retrieves information about the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", SetLastError = true)]
public static NTStatus NtQueryInformationProcess(
	IntPtr processHandle,
	ProcessInformationClass processInformationClass,
	ref ProcessBasicInformation refProcessInformation,
	int processInformationLength,
	ref int refReturnLength
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", SetLastError := true>]
Public Shared Function NtQueryInformationProcess ( 
	processHandle As IntPtr,
	processInformationClass As ProcessInformationClass,
	ByRef refProcessInformation As ProcessBasicInformation,
	processInformationLength As Integer,
	ByRef refReturnLength As Integer
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim processHandle As IntPtr
Dim processInformationClass As ProcessInformationClass
Dim refProcessInformation As ProcessBasicInformation
Dim processInformationLength As Integer
Dim refReturnLength As Integer
Dim returnValue As NTStatus

returnValue = NativeMethods.NtQueryInformationProcess(processHandle, 
	processInformationClass, refProcessInformation, 
	processInformationLength, refReturnLength)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", SetLastError = true)]
static NTStatus NtQueryInformationProcess(
	IntPtr processHandle, 
	ProcessInformationClass processInformationClass, 
	ProcessBasicInformation% refProcessInformation, 
	int processInformationLength, 
	int% refReturnLength
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", SetLastError = true)>]
static member NtQueryInformationProcess : 
        processHandle : IntPtr * 
        processInformationClass : ProcessInformationClass * 
        refProcessInformation : ProcessBasicInformation byref * 
        processInformationLength : int * 
        refReturnLength : int byref -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>processHandle</dt><dd>Type: System.IntPtr<br />A handle to the process for which information is to be retrieved.</dd><dt>processInformationClass</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessInformationClass">DevCase.Interop.Unmanaged.Win32.Enums.ProcessInformationClass</a><br />The type of process information to be retrieved.</dd><dt>refProcessInformation</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessBasicInformation">DevCase.Interop.Unmanaged.Win32.Structures.ProcessBasicInformation</a><br />A pointer to a buffer supplied by the calling application into which the function writes the requested information. 

 The size of the information written varies depending on the data type of the *processInformationClass* parameter.</dd><dt>processInformationLength</dt><dd>Type: System.Int32<br />The size of the buffer pointed to by the *refProcessInformation* parameter, in bytes.</dd><dt>refReturnLength</dt><dd>Type: System.Int32<br />A pointer to a variable in which the function returns the size of the requested information. 

 If the function was successful, this is the size of the information written to the buffer pointed to by the *refProcessInformation* parameter, but if the buffer was too small, this is the minimum size of buffer needed to receive the information successfully.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />The function returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> success or error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winternl/nf-winternl-ntqueryinformationprocess" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winternl/nf-winternl-ntqueryinformationprocess</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />