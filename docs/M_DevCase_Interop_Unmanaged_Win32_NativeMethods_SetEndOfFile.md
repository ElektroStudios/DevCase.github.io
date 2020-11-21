# NativeMethods.SetEndOfFile Method 
 

Sets the physical file size for the specified file to the current position of the file pointer. 

 The physical file size is also referred to as the end of the file. 

 The SetEndOfFile(IntPtr) function can be used to truncate or extend a file. To set the logical end of a file, use the SetFileValidData function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetEndOfFile(
	IntPtr hFile
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetEndOfFile ( 
	hFile As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hFile As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SetEndOfFile(hFile)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetEndOfFile(
	[InAttribute] IntPtr hFile
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetEndOfFile : 
        hFile : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hFile</dt><dd>Type: System.IntPtr<br />A handle to the file to be extended or truncated. 

 The file handle must be created with the GENERIC_WRITE access right.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-setendoffile" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-setendoffile</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />