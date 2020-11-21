# NativeMethods.GlobalMemoryStatusEx Method 
 

Retrieves information about the system's current usage of both physical and virtual memory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool GlobalMemoryStatusEx(
	ref MemoryStatusEx refStatus
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function GlobalMemoryStatusEx ( 
	ByRef refStatus As MemoryStatusEx
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refStatus As MemoryStatusEx
Dim returnValue As Boolean

returnValue = NativeMethods.GlobalMemoryStatusEx(refStatus)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool GlobalMemoryStatusEx(
	MemoryStatusEx% refStatus
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member GlobalMemoryStatusEx : 
        refStatus : MemoryStatusEx byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refStatus</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx">DevCase.Interop.Unmanaged.Win32.Structures.MemoryStatusEx</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryStatusEx">MemoryStatusEx</a> structure that receives information about current memory availability.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 



## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-globalmemorystatusex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-globalmemorystatusex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />