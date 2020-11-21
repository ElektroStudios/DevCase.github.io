# NativeMethods.GetFileSizeEx Method 
 

Retrieves the size of the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool GetFileSizeEx(
	IntPtr hFile,
	out long fileSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetFileSizeEx ( 
	hFile As IntPtr,
	<OutAttribute> ByRef fileSize As Long
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hFile As IntPtr
Dim fileSize As Long
Dim returnValue As Boolean

returnValue = NativeMethods.GetFileSizeEx(hFile, 
	fileSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool GetFileSizeEx(
	[InAttribute] IntPtr hFile, 
	[OutAttribute] long long% fileSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetFileSizeEx : 
        hFile : IntPtr * 
        fileSize : int64 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hFile</dt><dd>Type: System.IntPtr<br />A handle to the file. 

 The handle must have been created with the `FILE_READ_ATTRIBUTES` access right or equivalent, or the caller must have sufficient permission on the directory that contains the file.</dd><dt>fileSize</dt><dd>Type: System.Int64<br />A Int64 that receives the file size, in bytes.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getfilesizeex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getfilesizeex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />