# NativeMethods.HeapQueryInformation Method 
 

Retrieves information about the specified heap.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool HeapQueryInformation(
	IntPtr hHeap,
	HeapInformationClass heapInformationClass,
	IntPtr heapInformation,
	uint heapInformationLength,
	out uint refReturnLength
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function HeapQueryInformation ( 
	hHeap As IntPtr,
	heapInformationClass As HeapInformationClass,
	heapInformation As IntPtr,
	heapInformationLength As UInteger,
	<OutAttribute> ByRef refReturnLength As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hHeap As IntPtr
Dim heapInformationClass As HeapInformationClass
Dim heapInformation As IntPtr
Dim heapInformationLength As UInteger
Dim refReturnLength As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.HeapQueryInformation(hHeap, 
	heapInformationClass, heapInformation, 
	heapInformationLength, refReturnLength)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool HeapQueryInformation(
	[InAttribute] IntPtr hHeap, 
	HeapInformationClass heapInformationClass, 
	IntPtr heapInformation, 
	unsigned int heapInformationLength, 
	[OutAttribute] unsigned int% refReturnLength
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member HeapQueryInformation : 
        hHeap : IntPtr * 
        heapInformationClass : HeapInformationClass * 
        heapInformation : IntPtr * 
        heapInformationLength : uint32 * 
        refReturnLength : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hHeap</dt><dd>Type: System.IntPtr<br />A handle to the heap whose information is to be retrieved. 

 This handle is returned by either the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcessHeap">GetProcessHeap()</a> function.</dd><dt>heapInformationClass</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapInformationClass">DevCase.Interop.Unmanaged.Win32.Enums.HeapInformationClass</a><br />The class of information to be retrieved.</dd><dt>heapInformation</dt><dd>Type: System.IntPtr<br />A pointer to a buffer that receives the heap information. 

 The format of this data depends on the value of the *heapInformationClass* parameter.</dd><dt>heapInformationLength</dt><dd>Type: System.UInt32<br />The size of the heap information being queried, in bytes.</dd><dt>refReturnLength</dt><dd>Type: System.UInt32<br />A pointer to a variable that receives the length of data written to the *heapInformation* buffer. 

 If the buffer is too small, the function fails and *refReturnLength* specifies the minimum size required for the buffer. 

 If you do not want to receive this information, specify 0 (zero).</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapqueryinformation" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapqueryinformation</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />