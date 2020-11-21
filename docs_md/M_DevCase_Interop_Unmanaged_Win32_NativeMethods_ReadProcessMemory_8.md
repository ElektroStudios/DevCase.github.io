# NativeMethods.ReadProcessMemory Method (SafeProcessHandle, UIntPtr, IntPtr, IntPtr, IntPtr)
 

Reads data from an area of memory in a specified process. 

 The entire area to be read must be accessible or the operation fails.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool ReadProcessMemory(
	SafeProcessHandle hProcess,
	UIntPtr baseAddress,
	IntPtr buffer,
	IntPtr size,
	ref IntPtr refNumberOfBytesRead
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function ReadProcessMemory ( 
	hProcess As SafeProcessHandle,
	baseAddress As UIntPtr,
	buffer As IntPtr,
	size As IntPtr,
	ByRef refNumberOfBytesRead As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As SafeProcessHandle
Dim baseAddress As UIntPtr
Dim buffer As IntPtr
Dim size As IntPtr
Dim refNumberOfBytesRead As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.ReadProcessMemory(hProcess, 
	baseAddress, buffer, size, refNumberOfBytesRead)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool ReadProcessMemory(
	[InAttribute] SafeProcessHandle^ hProcess, 
	[InAttribute] UIntPtr baseAddress, 
	IntPtr buffer, 
	IntPtr size, 
	IntPtr% refNumberOfBytesRead
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member ReadProcessMemory : 
        hProcess : SafeProcessHandle * 
        baseAddress : UIntPtr * 
        buffer : IntPtr * 
        size : IntPtr * 
        refNumberOfBytesRead : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: Microsoft.Win32.SafeHandles.SafeProcessHandle<br />A handle to the process with memory that is being read. 

 The handle must have PROCESS_VM_READ access to the process.</dd><dt>baseAddress</dt><dd>Type: System.UIntPtr<br />A pointer to the base address in the specified process from which to read. 

 Before any data transfer occurs, the system verifies that all data in the base address and memory of the specified size is accessible for read access, and if it is not accessible the function fails.</dd><dt>buffer</dt><dd>Type: System.IntPtr<br />A pointer to a buffer that receives the contents from the address space of the specified process.</dd><dt>size</dt><dd>Type: System.IntPtr<br />The number of bytes to be read from the specified process.</dd><dt>refNumberOfBytesRead</dt><dd>Type: System.IntPtr<br />A pointer to a variable that receives the number of bytes transferred into the specified buffer. 

 If *refNumberOfBytesRead* is `0`, the parameter is ignored.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) If the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680553%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680553%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReadProcessMemory">ReadProcessMemory Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />