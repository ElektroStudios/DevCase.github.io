# NativeMethods.HeapSetInformation Method 
 

Enables features for a specified heap.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool HeapSetInformation(
	IntPtr hHeap,
	HeapInformationClass heapInformationClass,
	IntPtr heapInformation,
	uint heapInformationLength
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function HeapSetInformation ( 
	hHeap As IntPtr,
	heapInformationClass As HeapInformationClass,
	heapInformation As IntPtr,
	heapInformationLength As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hHeap As IntPtr
Dim heapInformationClass As HeapInformationClass
Dim heapInformation As IntPtr
Dim heapInformationLength As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.HeapSetInformation(hHeap, 
	heapInformationClass, heapInformation, 
	heapInformationLength)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool HeapSetInformation(
	[InAttribute] IntPtr hHeap, 
	HeapInformationClass heapInformationClass, 
	[InAttribute] IntPtr heapInformation, 
	unsigned int heapInformationLength
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member HeapSetInformation : 
        hHeap : IntPtr * 
        heapInformationClass : HeapInformationClass * 
        heapInformation : IntPtr * 
        heapInformationLength : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>hHeap</dt><dd>Type: System.IntPtr<br />A handle to the heap where information is to be set. 

 This handle is returned by either the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcessHeap">GetProcessHeap()</a> function.</dd><dt>heapInformationClass</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapInformationClass">DevCase.Interop.Unmanaged.Win32.Enums.HeapInformationClass</a><br />The class of information to be set.</dd><dt>heapInformation</dt><dd>Type: System.IntPtr<br />The heap information buffer. 

 The format of this data depends on the value of the *heapInformationClass* parameter. 

 If the *heapInformationClass* parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapInformationClass">CompatibilityInformation</a>, the *heapInformation* parameter is a pointer to a `ULONG` variable. 

 If the *heapInformationClass* parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapInformationClass">EnableTerminationOnCorruption</a>, the *heapInformation* parameter should be `NULL` and *heapInformationLength* should be 0 (zero).</dd><dt>heapInformationLength</dt><dd>Type: System.UInt32<br />The size of the *heapInformation* buffer, in bytes.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapsetinformation" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapsetinformation</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />