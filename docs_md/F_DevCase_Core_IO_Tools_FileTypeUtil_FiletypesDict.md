# FileTypeUtil.FiletypesDict Field
 

A collection of known file types and its signatures. 

 The keys are the filetype extension, the values are an Array of file types which uses that extension.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static readonly Dictionary<string, FileType[]> FiletypesDict
```

**VB**<br />
``` VB
Public Shared ReadOnly FiletypesDict As Dictionary(Of String, FileType())
```

**VB Usage**<br />
``` VB Usage
Dim value As Dictionary(Of String, FileType())

value = FileTypeUtil.FiletypesDict

```

**C++**<br />
``` C++
public:
static initonly Dictionary<String^, array<FileType^>^>^ FiletypesDict
```

**F#**<br />
``` F#
static val FiletypesDict: Dictionary<string, FileType[]>
```


#### Field Value
Type: Dictionary(String, <a href="T_DevCase_Core_IO_FileType">FileType</a>[])

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileTypeUtil">FileTypeUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />