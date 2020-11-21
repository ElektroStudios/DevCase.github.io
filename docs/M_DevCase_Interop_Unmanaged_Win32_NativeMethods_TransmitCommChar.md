# NativeMethods.TransmitCommChar Method 
 

Transmits a specified character ahead of any pending data in the output buffer of the specified communications device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool TransmitCommChar(
	IntPtr hFile,
	byte char
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function TransmitCommChar ( 
	hFile As IntPtr,
	char As Byte
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hFile As IntPtr
Dim char As Byte
Dim returnValue As Boolean

returnValue = NativeMethods.TransmitCommChar(hFile, 
	char)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool TransmitCommChar(
	[InAttribute] IntPtr hFile, 
	unsigned char char
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member TransmitCommChar : 
        hFile : IntPtr * 
        char : byte -> bool 

```


#### Parameters
&nbsp;<dl><dt>hFile</dt><dd>Type: System.IntPtr<br />A handle to the communications device. The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateFile">CreateFile(String, FileAccessRights, FileShare, IntPtr, FileMode, CreateFileFlags, IntPtr)</a> function returns this handle.</dd><dt>char</dt><dd>Type: System.Byte<br />\[Missing <param name="char"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.TransmitCommChar(System.IntPtr,System.Byte)"\]</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-transmitcommchar" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-transmitcommchar</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />