# PeHeaderUtil.GetPEFileKind Method (FileInfo)
 

Gets the PEFileKinds of the specified .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PEFileKinds GetPEFileKind(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Function GetPEFileKind ( 
	file As FileInfo
) As PEFileKinds
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim returnValue As PEFileKinds

returnValue = PeHeaderUtil.GetPEFileKind(file)
```

**C++**<br />
``` C++
public:
static PEFileKinds GetPEFileKind(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member GetPEFileKind : 
        file : FileInfo -> PEFileKinds 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The assembly file.</dd></dl>

#### Return Value
Type: PEFileKinds<br />The resulting PEFileKinds.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assemblyFile As New FileInfo("C:\Assembly.exe")
Dim peFileKind As PEFileKinds = GetPEFileKind(assemblyFile)

Console.WriteLine(peFileKind.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil">PeHeaderUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetPEFileKind">GetPEFileKind Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework Namespace</a><br />