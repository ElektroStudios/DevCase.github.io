# FileUtil.Recycle Method (FileInfo, UIOption)
 

Sends the source file to the Recycle Bin.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Recycle(
	FileInfo file,
	UIOption uioption = UIOption.OnlyErrorDialogs
)
```

**VB**<br />
``` VB
Public Shared Sub Recycle ( 
	file As FileInfo,
	Optional uioption As UIOption = UIOption.OnlyErrorDialogs
)
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim uioption As UIOptionFileUtil.Recycle(file, uioption)
```

**C++**<br />
``` C++
public:
static void Recycle(
	FileInfo^ file, 
	UIOption uioption = UIOption::OnlyErrorDialogs
)
```

**F#**<br />
``` F#
static member Recycle : 
        file : FileInfo * 
        ?uioption : UIOption 
(* Defaults:
        let _uioption = defaultArg uioption UIOption.OnlyErrorDialogs
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd><dt>uioption (Optional)</dt><dd>Type: Microsoft.VisualBasic.FileIO.UIOption<br />\[Missing <param name="uioption"/> documentation for "M:DevCase.Core.IO.Tools.FileUtil.Recycle(System.IO.FileInfo,Microsoft.VisualBasic.FileIO.UIOption)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_Recycle">Recycle Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />