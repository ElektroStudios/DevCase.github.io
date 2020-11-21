# MP3ValWrapper.Fix Method (FileInfo, Boolean, Boolean)
 

Tries to fix problems in the specified audio file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Fix(
	FileInfo file,
	bool deleteBackupFile = false,
	bool preserveDatestamp = true
)
```

**VB**<br />
``` VB
Public Function Fix ( 
	file As FileInfo,
	Optional deleteBackupFile As Boolean = false,
	Optional preserveDatestamp As Boolean = true
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3ValWrapper
Dim file As FileInfo
Dim deleteBackupFile As Boolean
Dim preserveDatestamp As Boolean
Dim returnValue As Integer

returnValue = instance.Fix(file, deleteBackupFile, 
	preserveDatestamp)
```

**C++**<br />
``` C++
public:
int Fix(
	FileInfo^ file, 
	bool deleteBackupFile = false, 
	bool preserveDatestamp = true
)
```

**F#**<br />
``` F#
member Fix : 
        file : FileInfo * 
        ?deleteBackupFile : bool * 
        ?preserveDatestamp : bool 
(* Defaults:
        let _deleteBackupFile = defaultArg deleteBackupFile false
        let _preserveDatestamp = defaultArg preserveDatestamp true
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The audio file to analyze.</dd><dt>deleteBackupFile (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the generated .bak file is deleted after a successful fix.</dd><dt>preserveDatestamp (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the original filedate is preserved on the file after a successful fix.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Val_MP3ValWrapper">MP3ValWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Fix">Fix Overload</a><br /><a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val Namespace</a><br />