# FileUtil.Recycle Method (String, UIOption)
 

Sends the source file to the Recycle Bin.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Recycle(
	string filepath,
	UIOption uioption = UIOption.OnlyErrorDialogs
)
```

**VB**<br />
``` VB
Public Shared Sub Recycle ( 
	filepath As String,
	Optional uioption As UIOption = UIOption.OnlyErrorDialogs
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim uioption As UIOptionFileUtil.Recycle(filepath, uioption)
```

**C++**<br />
``` C++
public:
static void Recycle(
	String^ filepath, 
	UIOption uioption = UIOption::OnlyErrorDialogs
)
```

**F#**<br />
``` F#
static member Recycle : 
        filepath : string * 
        ?uioption : UIOption 
(* Defaults:
        let _uioption = defaultArg uioption UIOption.OnlyErrorDialogs
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file path.</dd><dt>uioption (Optional)</dt><dd>Type: Microsoft.VisualBasic.FileIO.UIOption<br />\[Missing <param name="uioption"/> documentation for "M:DevCase.Core.IO.Tools.FileUtil.Recycle(System.String,Microsoft.VisualBasic.FileIO.UIOption)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_Recycle">Recycle Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />