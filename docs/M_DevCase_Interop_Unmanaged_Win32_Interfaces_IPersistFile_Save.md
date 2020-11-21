# IPersistFile.Save Method 
 

Saves a copy of the object to the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
void Save(
	string fileName,
	bool remember
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Sub Save ( 
	fileName As String,
	remember As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPersistFile
Dim fileName As String
Dim remember As Boolean

instance.Save(fileName, remember)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
void Save(
	[InAttribute] String^ fileName, 
	[InAttribute] bool remember
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract Save : 
        fileName : string * 
        remember : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: System.String<br />The absolute path of the file to which the object should be saved. 

 If *fileName* is a null reference (`Nothing` in Visual Basic), the object should save its data to the current file, if there is one.</dd><dt>remember</dt><dd>Type: System.Boolean<br />Indicates whether the *fileName* parameter is to be used as the current working file. 

 If `true` (`True` in Visual Basic), *fileName* becomes the current file and the object should clear its dirty flag after the save. 

 If `false` (`False` in Visual Basic), this save operation is a `Save A Copy As` ... operation. In this case, the current file is unchanged and the object should not clear its dirty flag. 

 If *fileName* is a null reference (`Nothing` in Visual Basic), the implementation should ignore the *remember* flag.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile">IPersistFile Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />