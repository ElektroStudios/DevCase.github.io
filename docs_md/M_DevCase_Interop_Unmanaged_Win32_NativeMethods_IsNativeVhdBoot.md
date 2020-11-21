# NativeMethods.IsNativeVhdBoot Method 
 

Indicates if the operating system was booted from a Virtual Hard Disk (VHD) container

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool IsNativeVhdBoot(
	out bool refNativeVhdBoot
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function IsNativeVhdBoot ( 
	<OutAttribute> ByRef refNativeVhdBoot As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refNativeVhdBoot As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.IsNativeVhdBoot(refNativeVhdBoot)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool IsNativeVhdBoot(
	[OutAttribute] bool% refNativeVhdBoot
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member IsNativeVhdBoot : 
        refNativeVhdBoot : bool byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refNativeVhdBoot</dt><dd>Type: System.Boolean<br />Pointer to a variable that receives a boolean indicating whether or not the operating system was booted from a Virtual Hard Disk (VHD).</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operating system was a native Virtual Hard Disk (VHD) boot; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-isnativevhdboot" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-isnativevhdboot</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />