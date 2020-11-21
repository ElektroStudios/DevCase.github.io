# PeHeaderUtil.GetPEFileKind Method (String)
 

Gets the PEFileKinds of the specified .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PEFileKinds GetPEFileKind(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetPEFileKind ( 
	filepath As String
) As PEFileKinds
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As PEFileKinds

returnValue = PeHeaderUtil.GetPEFileKind(filepath)
```

**C++**<br />
``` C++
public:
static PEFileKinds GetPEFileKind(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetPEFileKind : 
        filepath : string -> PEFileKinds 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The assembly file path.</dd></dl>

#### Return Value
Type: PEFileKinds<br />The resulting PEFileKinds.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assemblyPath As String = "C:\Assembly.exe"
Dim peFileKind As PEFileKinds = GetPEFileKind(assemblyPath)

Console.WriteLine(peFileKind.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil">PeHeaderUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetPEFileKind">GetPEFileKind Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework Namespace</a><br />