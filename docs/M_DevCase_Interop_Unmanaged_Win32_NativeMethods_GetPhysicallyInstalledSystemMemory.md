# NativeMethods.GetPhysicallyInstalledSystemMemory Method 
 

Retrieves the amount of RAM that is physically installed on the computer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool GetPhysicallyInstalledSystemMemory(
	out ulong refTotalMemoryInKilobytes
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetPhysicallyInstalledSystemMemory ( 
	<OutAttribute> ByRef refTotalMemoryInKilobytes As ULong
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refTotalMemoryInKilobytes As ULong
Dim returnValue As Boolean

returnValue = NativeMethods.GetPhysicallyInstalledSystemMemory(refTotalMemoryInKilobytes)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool GetPhysicallyInstalledSystemMemory(
	[OutAttribute] unsigned long long% refTotalMemoryInKilobytes
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetPhysicallyInstalledSystemMemory : 
        refTotalMemoryInKilobytes : uint64 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refTotalMemoryInKilobytes</dt><dd>Type: System.UInt64<br />A pointer to a variable that receives the amount of physically installed RAM, in kilobytes</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getphysicallyinstalledsystemmemory" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getphysicallyinstalledsystemmemory</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />