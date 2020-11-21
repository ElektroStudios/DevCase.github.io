# NativeMethods.GetVolumeInformation Method 
 

Retrieves information about the file system and volume associated with the specified root directory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool GetVolumeInformation(
	string rootPathName,
	StringBuilder volumeNameBuffer,
	int volumeNameSize,
	ref uint refVolumeSerialNumber,
	ref int refMaximumComponentLength,
	ref VolumeInformationFlags refFileSystemFlags,
	StringBuilder fileSystemNameBuffer,
	int fileSystemNameSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetVolumeInformation ( 
	rootPathName As String,
	volumeNameBuffer As StringBuilder,
	volumeNameSize As Integer,
	ByRef refVolumeSerialNumber As UInteger,
	ByRef refMaximumComponentLength As Integer,
	ByRef refFileSystemFlags As VolumeInformationFlags,
	fileSystemNameBuffer As StringBuilder,
	fileSystemNameSize As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim rootPathName As String
Dim volumeNameBuffer As StringBuilder
Dim volumeNameSize As Integer
Dim refVolumeSerialNumber As UInteger
Dim refMaximumComponentLength As Integer
Dim refFileSystemFlags As VolumeInformationFlags
Dim fileSystemNameBuffer As StringBuilder
Dim fileSystemNameSize As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.GetVolumeInformation(rootPathName, 
	volumeNameBuffer, volumeNameSize, 
	refVolumeSerialNumber, refMaximumComponentLength, 
	refFileSystemFlags, fileSystemNameBuffer, 
	fileSystemNameSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool GetVolumeInformation(
	String^ rootPathName, 
	StringBuilder^ volumeNameBuffer, 
	int volumeNameSize, 
	unsigned int% refVolumeSerialNumber, 
	int% refMaximumComponentLength, 
	VolumeInformationFlags% refFileSystemFlags, 
	StringBuilder^ fileSystemNameBuffer, 
	int fileSystemNameSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetVolumeInformation : 
        rootPathName : string * 
        volumeNameBuffer : StringBuilder * 
        volumeNameSize : int * 
        refVolumeSerialNumber : uint32 byref * 
        refMaximumComponentLength : int byref * 
        refFileSystemFlags : VolumeInformationFlags byref * 
        fileSystemNameBuffer : StringBuilder * 
        fileSystemNameSize : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>rootPathName</dt><dd>Type: System.String<br />The root directory of the volume to be described. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the root of the current directory is used.</dd><dt>volumeNameBuffer</dt><dd>Type: System.Text.StringBuilder<br />A buffer that receives the name of a specified volume. 

 The buffer size is specified by the *volumeNameSize* parameter.</dd><dt>volumeNameSize</dt><dd>Type: System.Int32<br />The character length of the buffer specified in *volumeNameBuffer* parameter.</dd><dt>refVolumeSerialNumber</dt><dd>Type: System.UInt32<br />A variable that receives the volume serial number. 

 This parameter can be a null reference (`Nothing` in Visual Basic) if the serial number is not required.</dd><dt>refMaximumComponentLength</dt><dd>Type: System.Int32<br />A variable that receives the maximum character length of a file name component that a specified file system supports. 

 A file name component is the portion of a file name between backslashes.</dd><dt>refFileSystemFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_VolumeInformationFlags">DevCase.Interop.Unmanaged.Win32.Enums.VolumeInformationFlags</a><br />A variable that receives flags associated with the specified file system.</dd><dt>fileSystemNameBuffer</dt><dd>Type: System.Text.StringBuilder<br />A buffer that receives the name of the file system, for example, the `FAT` file system or the `NTFS` file system. 

 The buffer size is specified by the *fileSystemNameSize* parameter.</dd><dt>fileSystemNameSize</dt><dd>Type: System.Int32<br />The character length of the buffer specified in *fileSystemNameBuffer* parameter.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/aa364993%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/aa364993%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />