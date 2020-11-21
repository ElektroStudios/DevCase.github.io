# IPersistFile.Load Method 
 

Opens the specified file and initializes an object from the file contents.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
void Load(
	string fileName,
	uint mode
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Sub Load ( 
	fileName As String,
	mode As UInteger
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPersistFile
Dim fileName As String
Dim mode As UInteger

instance.Load(fileName, mode)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
void Load(
	[InAttribute] String^ fileName, 
	unsigned int mode
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract Load : 
        fileName : string * 
        mode : uint32 -> unit 

```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: System.String<br />The absolute path of the file to be opened.</dd><dt>mode</dt><dd>Type: System.UInt32<br />The access mode to be used when opening the file. 

 Possible values are taken from the `STGM` enumeration. 

 The method can treat this value as a suggestion, adding more restrictive permissions if necessary. 

 If *mode* is `0`, the implementation should open the file using whatever default permissions are used when a user opens the file.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile">IPersistFile Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />