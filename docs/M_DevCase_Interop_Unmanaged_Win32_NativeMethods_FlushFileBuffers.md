# NativeMethods.FlushFileBuffers Method 
 

Flushes the buffers of a specified file and causes all buffered data to be written to a file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool FlushFileBuffers(
	IntPtr hFile
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function FlushFileBuffers ( 
	hFile As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hFile As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.FlushFileBuffers(hFile)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool FlushFileBuffers(
	[InAttribute] IntPtr hFile
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member FlushFileBuffers : 
        hFile : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hFile</dt><dd>Type: System.IntPtr<br />A handle to the open file. 

 The file handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_StandardAccessRights">StandardRightsWrite</a> access right. 

 If *hFile* is a handle to a communications device, the function only flushes the transmit buffer. 

 If *hFile* is a handle to the server end of a named pipe, the function does not return until the client has read all buffered data from the pipe.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-flushfilebuffers" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-flushfilebuffers</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />