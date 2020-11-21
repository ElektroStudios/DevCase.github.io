# NativeMethods.GetCompressedFileSize Method 
 

Retrieves the actual number of bytes of disk storage used to store a specified file. 

 If the file is located on a volume that supports compression and the file is compressed, the value obtained is the compressed size of the specified file. 

 If the file is located on a volume that supports sparse files and the file is a sparse file, the value obtained is the sparse size of the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetCompressedFileSize(
	string fileName,
	out uint refFileSizeHigh
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetCompressedFileSize ( 
	fileName As String,
	<OutAttribute> ByRef refFileSizeHigh As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim fileName As String
Dim refFileSizeHigh As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetCompressedFileSize(fileName, 
	refFileSizeHigh)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetCompressedFileSize(
	String^ fileName, 
	[OutAttribute] unsigned int% refFileSizeHigh
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetCompressedFileSize : 
        fileName : string * 
        refFileSizeHigh : uint32 byref -> uint32 

```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: System.String<br />The name of the file. 

 Do not specify the name of a file on a nonseeking device, such as a pipe or a communications device, as its file size has no meaning. 

 This parameter may include the path. In the ANSI version of this function, the name is limited to MAX_PATH characters. To extend this limit to 32,767 wide characters, call the Unicode version of the function and prepend "\?" to the path.</dd><dt>refFileSizeHigh</dt><dd>Type: System.UInt32<br />The high-order DWORD of the compressed file size. 

 The function's return value is the low-order DWORD of the compressed file size. 

 This parameter can be NULL if the high-order DWORD of the compressed file size is not needed. 

 Files less than 4 gigabytes in size do not need the high-order DWORD.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the low-order DWORD of the actual number of bytes of disk storage used to store the specified file, and if lpFileSizeHigh is non-NULL, the function puts the high-order DWORD of that actual value into the DWORD pointed to by that parameter. This is the compressed file size for compressed files, the actual file size for noncompressed files. 

 If the function fails, and *refFileSizeHigh* is NULL, the return value is INVALID_FILE_SIZE. 

 If the return value is INVALID_FILE_SIZE and *refFileSizeHigh* is non-NULL, an application must call GetLastError to determine whether the function has succeeded (value is NO_ERROR) or failed (value is other than NO_ERROR).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getcompressedfilesizea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-getcompressedfilesizea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />