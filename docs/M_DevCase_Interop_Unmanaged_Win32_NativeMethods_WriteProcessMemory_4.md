# NativeMethods.WriteProcessMemory Method (IntPtr, UIntPtr, Byte[], IntPtr, IntPtr)
 

Writes data to an area of memory in a specified process. 

 The entire area to be written to must be accessible or the operation fails.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool WriteProcessMemory(
	IntPtr hProcess,
	UIntPtr baseAddress,
	byte[] buffer,
	IntPtr size,
	out IntPtr refNumberOfBytesWritten
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function WriteProcessMemory ( 
	hProcess As IntPtr,
	baseAddress As UIntPtr,
	buffer As Byte(),
	size As IntPtr,
	<OutAttribute> ByRef refNumberOfBytesWritten As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim baseAddress As UIntPtr
Dim buffer As Byte()
Dim size As IntPtr
Dim refNumberOfBytesWritten As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.WriteProcessMemory(hProcess, 
	baseAddress, buffer, size, refNumberOfBytesWritten)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool WriteProcessMemory(
	[InAttribute] IntPtr hProcess, 
	[InAttribute] UIntPtr baseAddress, 
	array<unsigned char>^ buffer, 
	IntPtr size, 
	[OutAttribute] IntPtr% refNumberOfBytesWritten
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member WriteProcessMemory : 
        hProcess : IntPtr * 
        baseAddress : UIntPtr * 
        buffer : byte[] * 
        size : IntPtr * 
        refNumberOfBytesWritten : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process memory to be modified. 

 The handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryWrite</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a> access to the process.</dd><dt>baseAddress</dt><dd>Type: System.UIntPtr<br />A pointer to the base address in the specified process to which data is written. 

 Before data transfer occurs, the system verifies that all data in the base address and memory of the specified size is accessible for write access, and if it is not accessible, the function fails.</dd><dt>buffer</dt><dd>Type: System.Byte[]<br />A pointer to the buffer that contains data to be written in the address space of the specified process.</dd><dt>size</dt><dd>Type: System.IntPtr<br />The number of bytes to be written to the specified process.</dd><dt>refNumberOfBytesWritten</dt><dd>Type: System.IntPtr<br />A pointer to a variable that receives the number of bytes transferred into the specified process. 

 This parameter is optional. 

 If *refNumberOfBytesWritten* is Zero, the parameter is ignored.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms681674%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms681674%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_WriteProcessMemory">WriteProcessMemory Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />