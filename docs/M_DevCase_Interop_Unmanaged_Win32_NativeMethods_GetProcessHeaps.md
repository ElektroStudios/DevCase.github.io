# NativeMethods.GetProcessHeaps Method 
 

Returns the number of active heaps and retrieves handles to all of the active heaps for the calling process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static uint GetProcessHeaps(
	[OptionalAttribute] uint numberOfHeaps,
	[OptionalAttribute] IntPtr[] processHeaps
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function GetProcessHeaps ( 
	<OptionalAttribute> numberOfHeaps As UInteger,
	<OptionalAttribute> processHeaps As IntPtr()
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim numberOfHeaps As UInteger
Dim processHeaps As IntPtr()
Dim returnValue As UInteger

returnValue = NativeMethods.GetProcessHeaps(numberOfHeaps, 
	processHeaps)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static unsigned int GetProcessHeaps(
	[OptionalAttribute] unsigned int numberOfHeaps, 
	[OptionalAttribute] array<IntPtr>^ processHeaps
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member GetProcessHeaps : 
        [<OptionalAttribute>] numberOfHeaps : uint32 * 
        [<OptionalAttribute>] processHeaps : IntPtr[] -> uint32 

```


#### Parameters
&nbsp;<dl><dt>numberOfHeaps (Optional)</dt><dd>Type: System.UInt32<br />The maximum number of heap handles that can be stored into the buffer pointed to by ProcessHeaps.</dd><dt>processHeaps (Optional)</dt><dd>Type: System.IntPtr[]<br />A pointer to a buffer that receives an array of heap handles.</dd></dl>

#### Return Value
Type: UInt32<br />The return value is the number of handles to heaps that are active for the calling process. 

 If the return value is less than or equal to *numberOfHeaps*, the function has stored that number of heap handles in the buffer pointed to by *processHeaps*. 

 If the return value is greater than *numberOfHeaps*, the buffer pointed to by *processHeaps* is too small to hold all the heap handles for the calling process, and the function stores *numberOfHeaps* handles in the buffer. 

 Use the return value to allocate a buffer that is large enough to receive all of the handles, and call the function again. 

 If the return value is zero, the function has failed because every process has at least one active heap, the default heap for the process.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-getprocessheaps" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-getprocessheaps</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />