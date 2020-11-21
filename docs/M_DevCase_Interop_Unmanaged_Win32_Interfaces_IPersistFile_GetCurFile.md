# IPersistFile.GetCurFile Method 
 

Retrieves the current name of the file associated with the object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
void GetCurFile(
	string fileName
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Sub GetCurFile ( 
	fileName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPersistFile
Dim fileName As String

instance.GetCurFile(fileName)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
void GetCurFile(
	[InAttribute] String^ fileName
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetCurFile : 
        fileName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: System.String<br />The path for the current file or the default file name prompt (such as `*.txt`). 

 If an error occurs, *fileName* is set to a null reference (`Nothing` in Visual Basic).</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile">IPersistFile Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />