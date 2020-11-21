# IPersistFile.SaveCompleted Method 
 

Notifies the object that it can write to its file. 

 It does this by notifying the object that it can revert from `NoScribble` mode (in which it must not write to its file), to `Normal` mode (in which it can). 

 The component enters `NoScribble` mode when it receives an <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_Save">Save(String, Boolean)</a> call.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
void SaveCompleted(
	string fileName
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Sub SaveCompleted ( 
	fileName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPersistFile
Dim fileName As String

instance.SaveCompleted(fileName)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
void SaveCompleted(
	[InAttribute] String^ fileName
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract SaveCompleted : 
        fileName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: System.String<br />The absolute path of the file where the object was saved previously.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile">IPersistFile Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />