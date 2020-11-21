# DeviceUtil.FormatDrive Method 
 

Formats a drive.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DriveFormatResult FormatDrive(
	char driveLetter,
	bool quickFormat,
	DriveFileSystem fileSystem = DriveFileSystem.NTFS,
	int clusterSize = 0,
	string volumeLabel = "",
	bool enableCompression = false
)
```

**VB**<br />
``` VB
Public Shared Function FormatDrive ( 
	driveLetter As Char,
	quickFormat As Boolean,
	Optional fileSystem As DriveFileSystem = DriveFileSystem.NTFS,
	Optional clusterSize As Integer = 0,
	Optional volumeLabel As String = "",
	Optional enableCompression As Boolean = false
) As DriveFormatResult
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim quickFormat As Boolean
Dim fileSystem As DriveFileSystem
Dim clusterSize As Integer
Dim volumeLabel As String
Dim enableCompression As Boolean
Dim returnValue As DriveFormatResult

returnValue = DeviceUtil.FormatDrive(driveLetter, 
	quickFormat, fileSystem, clusterSize, 
	volumeLabel, enableCompression)
```

**C++**<br />
``` C++
public:
static DriveFormatResult FormatDrive(
	wchar_t driveLetter, 
	bool quickFormat, 
	DriveFileSystem fileSystem = DriveFileSystem::NTFS, 
	int clusterSize = 0, 
	String^ volumeLabel = L"", 
	bool enableCompression = false
)
```

**F#**<br />
``` F#
static member FormatDrive : 
        driveLetter : char * 
        quickFormat : bool * 
        ?fileSystem : DriveFileSystem * 
        ?clusterSize : int * 
        ?volumeLabel : string * 
        ?enableCompression : bool 
(* Defaults:
        let _fileSystem = defaultArg fileSystem DriveFileSystem.NTFS
        let _clusterSize = defaultArg clusterSize 0
        let _volumeLabel = defaultArg volumeLabel ""
        let _enableCompression = defaultArg enableCompression false
*)
-> DriveFormatResult 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The drive letter to format.</dd><dt>quickFormat</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), formats the volume with a quick format by removing files from the disk without scanning the disk for bad sectors. 

 Use this option only if the disk has been previously formatted, and you know that the disk is not damaged. 

 The default value is `true` (`True` in Visual Basic).</dd><dt>fileSystem (Optional)</dt><dd>Type: <a href="T_DevCase_Core_IO_DriveFileSystem">DevCase.Core.IO.DriveFileSystem</a><br />The filesystem format to use for this volume. 

 Default value is <a href="T_DevCase_Core_IO_DriveFileSystem">NTFS</a>.</dd><dt>clusterSize (Optional)</dt><dd>Type: System.Int32<br />The disk allocation unit size—cluster size. 

 All of the filesystems organizes the hard disk based on cluster size, which represents the smallest amount of disk space that can be allocated to hold a file. 

 The smaller the cluster size you use, the more efficiently your disk stores information. 

 If no cluster size is specified during format, Windows picks defaults based on the size of the volume. These defaults have been selected to reduce the amount of space lost and to reduce fragmentation. 

 For general use, the default settings are strongly recommended.</dd><dt>volumeLabel (Optional)</dt><dd>Type: System.String<br />The label to use for the new volume. 

 The volume label can contain up to `11` characters for FAT16 and FAT32 volumes, and up to `32` characters for NTFS filesystem volumes.</dd><dt>enableCompression (Optional)</dt><dd>Type: System.Boolean<br />Not implemented.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_IO_DriveFormatResult">DriveFormatResult</a><br />If format success, the return value is <a href="T_DevCase_Core_IO_DriveFormatResult">Success</a>; otherwise; a <a href="T_DevCase_Core_IO_DriveFormatResult">DriveFormatResult</a> value indicating the error.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Volume-label for X filesystem can't be larger than Y characters.;volumeLabel</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/aa390432%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/aa390432%28v=vs.85%29.aspx</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As DriveFormatResult =
    FormatDrive(driveLetter:="Z"c, quickFormat:=True,
                             fileSystem:=DriveFileSystem.Ntfs,
                             clusterSize:=4096, volumeLabel:="Drive Z")
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />