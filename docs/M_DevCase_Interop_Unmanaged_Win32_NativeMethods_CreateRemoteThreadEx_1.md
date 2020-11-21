# NativeMethods.CreateRemoteThreadEx Method (IntPtr, SecurityAttributes, IntPtr, ThreadStart, IntPtr, CreateThreadFlags, IntPtr, UInt32)
 

Creates a thread that runs in the virtual address space of another process and optionally specifies extended attributes such as processor group affinity.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr CreateRemoteThreadEx(
	IntPtr hProcess,
	SecurityAttributes threadAttributes,
	IntPtr stackSize,
	ThreadStart startAddress,
	IntPtr parameter,
	CreateThreadFlags creationFlags,
	IntPtr attributeList,
	out uint refThreadId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function CreateRemoteThreadEx ( 
	hProcess As IntPtr,
	threadAttributes As SecurityAttributes,
	stackSize As IntPtr,
	startAddress As ThreadStart,
	parameter As IntPtr,
	creationFlags As CreateThreadFlags,
	attributeList As IntPtr,
	<OutAttribute> ByRef refThreadId As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim threadAttributes As SecurityAttributes
Dim stackSize As IntPtr
Dim startAddress As ThreadStart
Dim parameter As IntPtr
Dim creationFlags As CreateThreadFlags
Dim attributeList As IntPtr
Dim refThreadId As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateRemoteThreadEx(hProcess, 
	threadAttributes, stackSize, startAddress, 
	parameter, creationFlags, attributeList, 
	refThreadId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr CreateRemoteThreadEx(
	[InAttribute] IntPtr hProcess, 
	[InAttribute] SecurityAttributes threadAttributes, 
	IntPtr stackSize, 
	ThreadStart^ startAddress, 
	[InAttribute] IntPtr parameter, 
	CreateThreadFlags creationFlags, 
	IntPtr attributeList, 
	[OutAttribute] unsigned int% refThreadId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member CreateRemoteThreadEx : 
        hProcess : IntPtr * 
        threadAttributes : SecurityAttributes * 
        stackSize : IntPtr * 
        startAddress : ThreadStart * 
        parameter : IntPtr * 
        creationFlags : CreateThreadFlags * 
        attributeList : IntPtr * 
        refThreadId : uint32 byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">CreateThread</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryWrite</a>, and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a> access rights.</dd><dt>threadAttributes</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">DevCase.Interop.Unmanaged.Win32.Structures.SecurityAttributes</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes</a> structure that specifies a security descriptor for the new thread and determines whether child processes can inherit the returned handle. 

 If *threadAttributes* is NULL, the thread gets a default security descriptor and the handle cannot be inherited. 

 The access control lists (ACL) in the default security descriptor for a thread come from the primary token of the creator.</dd><dt>stackSize</dt><dd>Type: System.IntPtr<br />The initial size of the stack, in bytes. 

 The system rounds this value to the nearest page. 

 If this parameter is 0 (zero), the new thread uses the default size for the executable.</dd><dt>startAddress</dt><dd>Type: System.Threading.ThreadStart<br />A pointer to the application-defined function of type LPTHREAD_START_ROUTINE to be executed by the thread and represents the starting address of the thread in the remote process. 

 The function must exist in the remote process.</dd><dt>parameter</dt><dd>Type: System.IntPtr<br />A pointer to a variable to be passed to the thread function pointed to by *startAddress*. 

 This parameter can be NULL.</dd><dt>creationFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CreateThreadFlags">DevCase.Interop.Unmanaged.Win32.Enums.CreateThreadFlags</a><br />The flags that control the creation of the thread.</dd><dt>attributeList</dt><dd>Type: System.IntPtr<br />An attribute list that contains additional parameters for the new thread. 

 This list is created by the InitializeProcThreadAttributeList function.</dd><dt>refThreadId</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the thread identifier. 

 If this parameter is NULL, the thread identifier is not returned.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the new thread. 

 If the function fails, the return value is NULL.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-createremotethreadex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-createremotethreadex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateRemoteThreadEx">CreateRemoteThreadEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />