# NativeMethods.CreateRemoteThread Method (IntPtr, IntPtr, IntPtr, ThreadStart, IntPtr, CreateThreadFlags, UInt32)
 

Creates a thread that runs in the virtual address space of another process. 

 Use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateRemoteThreadEx">CreateRemoteThreadEx(IntPtr, SecurityAttributes, IntPtr, IntPtr, IntPtr, CreateThreadFlags, IntPtr, UInt32)</a> function to create a thread that runs in the virtual address space of another process and optionally specify extended attributes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static IntPtr CreateRemoteThread(
	IntPtr hProcess,
	IntPtr threadAttributes,
	IntPtr stackSize,
	ThreadStart startAddress,
	IntPtr threadParameter,
	CreateThreadFlags creationFlags,
	ref uint refThreadId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function CreateRemoteThread ( 
	hProcess As IntPtr,
	threadAttributes As IntPtr,
	stackSize As IntPtr,
	startAddress As ThreadStart,
	threadParameter As IntPtr,
	creationFlags As CreateThreadFlags,
	ByRef refThreadId As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim threadAttributes As IntPtr
Dim stackSize As IntPtr
Dim startAddress As ThreadStart
Dim threadParameter As IntPtr
Dim creationFlags As CreateThreadFlags
Dim refThreadId As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateRemoteThread(hProcess, 
	threadAttributes, stackSize, startAddress, 
	threadParameter, creationFlags, 
	refThreadId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static IntPtr CreateRemoteThread(
	IntPtr hProcess, 
	IntPtr threadAttributes, 
	IntPtr stackSize, 
	ThreadStart^ startAddress, 
	IntPtr threadParameter, 
	CreateThreadFlags creationFlags, 
	unsigned int% refThreadId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member CreateRemoteThread : 
        hProcess : IntPtr * 
        threadAttributes : IntPtr * 
        stackSize : IntPtr * 
        startAddress : ThreadStart * 
        threadParameter : IntPtr * 
        creationFlags : CreateThreadFlags * 
        refThreadId : uint32 byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process in which the thread is to be created. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">CreateThread</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a>, and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryWrite</a> access rights, and may fail without these rights on certain platforms.</dd><dt>threadAttributes</dt><dd>Type: System.IntPtr<br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes</a> structure that specifies a security descriptor for the new thread and determines whether child processes can inherit the returned handle. 

 If *threadAttributes* is Zero, the thread gets a default security descriptor and the handle cannot be inherited. 

 The access control lists (ACL) in the default security descriptor for a thread come from the primary token of the creator.</dd><dt>stackSize</dt><dd>Type: System.IntPtr<br />The initial size of the stack, in bytes. The system rounds this value to the nearest page. 

 If this parameter is 0 (zero), the new thread uses the default size for the executable.</dd><dt>startAddress</dt><dd>Type: System.Threading.ThreadStart<br />A pointer to the application-defined function of type `LPTHREAD_START_ROUTINE` to be executed by the thread and represents the starting address of the thread in the remote process. 

 The function must exist in the remote process.</dd><dt>threadParameter</dt><dd>Type: System.IntPtr<br />A pointer to a variable to be passed to the thread function.</dd><dt>creationFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CreateThreadFlags">DevCase.Interop.Unmanaged.Win32.Enums.CreateThreadFlags</a><br />The flags that control the creation of the thread.</dd><dt>refThreadId</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the thread identifier. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the thread identifier is not returned.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the new thread. 

 If the function fails, the return value is NULL. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms682453(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms682453(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateRemoteThread">CreateRemoteThread Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />