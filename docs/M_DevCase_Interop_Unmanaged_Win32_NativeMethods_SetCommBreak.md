# NativeMethods.SetCommBreak Method 
 

Suspends character transmission for a specified communications device and places the transmission line in a break state until the ClearCommBreak function is called.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetCommBreak(
	IntPtr hFile
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetCommBreak ( 
	hFile As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hFile As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SetCommBreak(hFile)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetCommBreak(
	[InAttribute] IntPtr hFile
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetCommBreak : 
        hFile : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hFile</dt><dd>Type: System.IntPtr<br />A handle to the communications device. The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateFile">CreateFile(String, FileAccessRights, FileShare, IntPtr, FileMode, CreateFileFlags, IntPtr)</a> function returns this handle.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the Function fails, the Return value Is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-setcommbreak" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-setcommbreak</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />