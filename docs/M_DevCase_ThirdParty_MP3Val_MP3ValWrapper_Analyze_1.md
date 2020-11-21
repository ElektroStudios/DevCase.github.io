# MP3ValWrapper.Analyze Method (String)
 

Analyzes a file for errors.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Analyze(
	string filepath
)
```

**VB**<br />
``` VB
Public Function Analyze ( 
	filepath As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3ValWrapper
Dim filepath As String
Dim returnValue As Integer

returnValue = instance.Analyze(filepath)
```

**C++**<br />
``` C++
public:
int Analyze(
	String^ filepath
)
```

**F#**<br />
``` F#
member Analyze : 
        filepath : string -> int 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The audio filepath to analyze.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Val_MP3ValWrapper">MP3ValWrapper Class</a><br /><a href="Overload_DevCase_ThirdParty_MP3Val_MP3ValWrapper_Analyze">Analyze Overload</a><br /><a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val Namespace</a><br />