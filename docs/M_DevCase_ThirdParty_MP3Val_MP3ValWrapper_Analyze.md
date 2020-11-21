# MP3ValWrapper.Analyze Method (FileInfo)
 

Analyzes a file for errors.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Analyze(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Function Analyze ( 
	file As FileInfo
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3ValWrapper
Dim file As FileInfo
Dim returnValue As Integer

returnValue = instance.Analyze(file)
```

**C++**<br />
``` C++
public:
int Analyze(
	FileInfo^ file
)
```

**F#**<br />
``` F#
member Analyze : 
        file : FileInfo -> int 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The audio file to analyze.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Val_MP3ValWrapper">MP3ValWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Analyze">Analyze Overload</a><br /><a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val Namespace</a><br />