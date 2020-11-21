# NativeMethods.GetLogicalDrives Method 
 

Retrieves a bitmask representing the currently available disk drives.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static uint GetLogicalDrives()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetLogicalDrives As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetLogicalDrives()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static unsigned int GetLogicalDrives()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetLogicalDrives : unit -> uint32 

```


#### Return Value
Type: UInt32<br />If the function succeeds, the return value is a bitmask representing the currently available disk drives. Bit position 0 (the least-significant bit) is drive A, bit position 1 is drive B, bit position 2 is drive C, and so on. 

 If the function fails, the return value is zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getlogicaldrives" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getlogicaldrives</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />