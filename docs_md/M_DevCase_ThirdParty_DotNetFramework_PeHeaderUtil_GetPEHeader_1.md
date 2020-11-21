# PeHeaderUtil.GetPEHeader Method (String)
 

Gets the PE header of the specified .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PEHeaders GetPEHeader(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetPEHeader ( 
	filepath As String
) As PEHeaders
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As PEHeaders

returnValue = PeHeaderUtil.GetPEHeader(filepath)
```

**C++**<br />
``` C++
public:
static PEHeaders^ GetPEHeader(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetPEHeader : 
        filepath : string -> PEHeaders 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The assembly file path.</dd></dl>

#### Return Value
Type: PEHeaders<br />The resulting PEHeaders.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assemblyPath As String = "C:\Assembly.exe"
Dim peHeader As PEHeaders = GetPEHeader(assemblyPath)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil">PeHeaderUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetPEHeader">GetPEHeader Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework Namespace</a><br />