# NativeMethods.HeapCreate Method 
 

Creates a private heap object that can be used by the calling process. 

 The function reserves space in the virtual address space of the process and allocates physical storage for a specified initial portion of this block.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static IntPtr HeapCreate(
	HeapFlags options,
	uint initialSize,
	uint maximumSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function HeapCreate ( 
	options As HeapFlags,
	initialSize As UInteger,
	maximumSize As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim options As HeapFlags
Dim initialSize As UInteger
Dim maximumSize As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.HeapCreate(options, 
	initialSize, maximumSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static IntPtr HeapCreate(
	HeapFlags options, 
	unsigned int initialSize, 
	unsigned int maximumSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member HeapCreate : 
        options : HeapFlags * 
        initialSize : uint32 * 
        maximumSize : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>options</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags</a><br />The heap allocation options. 

 These options affect subsequent access to the new heap through calls to the heap functions.</dd><dt>initialSize</dt><dd>Type: System.UInt32<br />The initial size of the heap, in bytes. 

 This value determines the initial amount of memory that is committed for the heap. 

 The value is rounded up to a multiple of the system page size. 

 The value must be smaller than *maximumSize*. 

 If this parameter is 0, the function commits one page. 

 To determine the size of a page on the host computer, use the GetSystemInfo function.</dd><dt>maximumSize</dt><dd>Type: System.UInt32<br />The maximum size of the heap, in bytes. 

 The HeapCreate(HeapFlags, UInt32, UInt32) function rounds *maximumSize* up to a multiple of the system page size and then reserves a block of that size in the process's virtual address space for the heap. 

 If allocation requests made by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapAlloc">HeapAlloc(IntPtr, HeapFlags, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapReAlloc">HeapReAlloc(IntPtr, HeapFlags, IntPtr, UInt32)</a> functions exceed the size specified by *initialSize*, the system commits additional pages of memory for the heap, up to the heap's maximum size. 

 If *maximumSize* is not zero, the heap size is fixed and cannot grow beyond the maximum size. Also, the largest memory block that can be allocated from the heap is slightly less than 512 KB for a 32-bit process and slightly less than 1,024 KB for a 64-bit process. Requests to allocate larger blocks fail, even if the maximum size of the heap is large enough to contain the block. 

 If *maximumSize* is 0, the heap can grow in size. The heap's size is limited only by the available memory. 

 Requests to allocate memory blocks larger than the limit for a fixed-size heap do not automatically fail; instead, the system calls the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function to obtain the memory that is needed for large blocks. 

 Applications that need to allocate large memory blocks should set *maximumSize* to 0.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the newly created heap. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapcreate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapcreate</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />