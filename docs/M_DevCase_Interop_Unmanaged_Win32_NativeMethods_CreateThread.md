# NativeMethods.CreateThread Method (SecurityAttributes, IntPtr, IntPtr, IntPtr, CreateThreadFlags, UInt32)
 

Creates a thread to execute within the virtual address space of the calling process. 

 To create a thread that runs in the virtual address space of another process, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateRemoteThread">CreateRemoteThread(IntPtr, SecurityAttributes, IntPtr, IntPtr, IntPtr, CreateThreadFlags, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static IntPtr CreateThread(
	in SecurityAttributes refThreadAttributes,
	IntPtr stackSize,
	IntPtr startAddress,
	IntPtr threadParameter,
	CreateThreadFlags creationFlags,
	ref uint refThreadId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function CreateThread ( 
	ByRef refThreadAttributes As SecurityAttributes,
	stackSize As IntPtr,
	startAddress As IntPtr,
	threadParameter As IntPtr,
	creationFlags As CreateThreadFlags,
	ByRef refThreadId As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim refThreadAttributes As SecurityAttributes
Dim stackSize As IntPtr
Dim startAddress As IntPtr
Dim threadParameter As IntPtr
Dim creationFlags As CreateThreadFlags
Dim refThreadId As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateThread(refThreadAttributes, 
	stackSize, startAddress, threadParameter, 
	creationFlags, refThreadId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static IntPtr CreateThread(
	[InAttribute] SecurityAttributes% refThreadAttributes, 
	IntPtr stackSize, 
	IntPtr startAddress, 
	IntPtr threadParameter, 
	CreateThreadFlags creationFlags, 
	unsigned int% refThreadId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member CreateThread : 
        refThreadAttributes : SecurityAttributes byref * 
        stackSize : IntPtr * 
        startAddress : IntPtr * 
        threadParameter : IntPtr * 
        creationFlags : CreateThreadFlags * 
        refThreadId : uint32 byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>refThreadAttributes</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">DevCase.Interop.Unmanaged.Win32.Structures.SecurityAttributes</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes</a> structure that determines whether the returned handle can be inherited by child processes. 

 If *refThreadAttributes* is a null reference (`Nothing` in Visual Basic), the handle cannot be inherited. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes_SecurityDescriptor">SecurityDescriptor</a> member of the structure specifies a security descriptor for the new thread. 

 If *refThreadAttributes* is a null reference (`Nothing` in Visual Basic), the thread gets a default security descriptor. The ACLs in the default security descriptor for a thread come from the primary token of the creator.</dd><dt>stackSize</dt><dd>Type: System.IntPtr<br />The initial size of the stack, in bytes. The system rounds this value to the nearest page. 

 If this parameter is zero, the new thread uses the default size for the executable.</dd><dt>startAddress</dt><dd>Type: System.IntPtr<br />A pointer to the application-defined function to be executed by the thread. 

 This pointer represents the starting address of the thread.</dd><dt>threadParameter</dt><dd>Type: System.IntPtr<br />A pointer to a variable to be passed to the thread.</dd><dt>creationFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CreateThreadFlags">DevCase.Interop.Unmanaged.Win32.Enums.CreateThreadFlags</a><br />The flags that control the creation of the thread.</dd><dt>refThreadId</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the thread identifier. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the thread identifier is not returned.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the new thread. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms682453(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms682453(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateThread">CreateThread Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />