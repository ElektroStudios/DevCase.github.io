# NativeMethods.GetFileSize Method 
 

**Note: This API is now obsolete.**

Retrieves the size of the specified file, in bytes. 

 It is recommended that you use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetFileSizeEx">GetFileSizeEx(IntPtr, Int64)</a> instead.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
[ObsoleteAttribute("Call NativeMethods.GetFileSize() instead", true)]
public static uint GetFileSize(
	IntPtr hFile,
	out uint fileSizeHigh
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
<ObsoleteAttribute("Call NativeMethods.GetFileSize() instead", true)>
Public Shared Function GetFileSize ( 
	hFile As IntPtr,
	<OutAttribute> ByRef fileSizeHigh As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hFile As IntPtr
Dim fileSizeHigh As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetFileSize(hFile, 
	fileSizeHigh)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
[ObsoleteAttribute(L"Call NativeMethods.GetFileSize() instead", true)]
static unsigned int GetFileSize(
	[InAttribute] IntPtr hFile, 
	[OutAttribute] unsigned int% fileSizeHigh
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
[<ObsoleteAttribute("Call NativeMethods.GetFileSize() instead", true)>]
static member GetFileSize : 
        hFile : IntPtr * 
        fileSizeHigh : uint32 byref -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hFile</dt><dd>Type: System.IntPtr<br />A handle to the file.</dd><dt>fileSizeHigh</dt><dd>Type: System.UInt32<br />A pointer to the variable where the high-order doubleword of the file size is returned. 

 This parameter can be `NULL` if the application does not require the high-order doubleword.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the low-order doubleword of the file size, and, if *fileSizeHigh* is non-`NULL`, the function puts the high-order doubleword of the file size into the variable pointed to by that parameter. 

 If the function fails and *fileSizeHigh* is `NULL`, the return value is `INVALID_FILE_SIZE`. 

 When *fileSizeHigh* is `NULL`, the results returned for large files are ambiguous, and you will not be able to determine the actual size of the file. It is recommended that you use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetFileSizeEx">GetFileSizeEx(IntPtr, Int64)</a> instead. 

 If the function fails and *fileSizeHigh* is non-`NULL`, the return value is `INVALID_FILE_SIZE` and `GetLastError` will return a value other than `NO_ERROR`.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getfilesize" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getfilesize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />