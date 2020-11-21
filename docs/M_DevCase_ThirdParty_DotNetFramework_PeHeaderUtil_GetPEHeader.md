# PeHeaderUtil.GetPEHeader Method (FileInfo)
 

Gets the PE header of the specified .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PEHeaders GetPEHeader(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Function GetPEHeader ( 
	file As FileInfo
) As PEHeaders
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim returnValue As PEHeaders

returnValue = PeHeaderUtil.GetPEHeader(file)
```

**C++**<br />
``` C++
public:
static PEHeaders^ GetPEHeader(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member GetPEHeader : 
        file : FileInfo -> PEHeaders 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The assembly file.</dd></dl>

#### Return Value
Type: PEHeaders<br />The resulting PEHeaders.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assemblyFile As New FileInfo("C:\Assembly.exe")
Dim peHeader As PEHeaders = GetPEHeader(assemblyFile)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil">PeHeaderUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetPEHeader">GetPEHeader Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework Namespace</a><br />