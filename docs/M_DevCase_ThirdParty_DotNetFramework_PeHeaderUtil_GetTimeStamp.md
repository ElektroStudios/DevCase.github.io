# PeHeaderUtil.GetTimeStamp Method (FileInfo)
 

Gets the compilation timestamp of the specified .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DateTimeOffset GetTimeStamp(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Function GetTimeStamp ( 
	file As FileInfo
) As DateTimeOffset
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim returnValue As DateTimeOffset

returnValue = PeHeaderUtil.GetTimeStamp(file)
```

**C++**<br />
``` C++
public:
static DateTimeOffset GetTimeStamp(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member GetTimeStamp : 
        file : FileInfo -> DateTimeOffset 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The assembly file.</dd></dl>

#### Return Value
Type: DateTimeOffset<br />The resulting timestamp.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assemblyFile As New FileInfo("C:\Assembly.exe")
Dim timeStamp As DateTimeOffset = GetTimeStamp(assemblyFile)

Console.WriteLine(timeStamp.ToString("dd/MMMM/yyyy HH:mm:ss", CultureInfo.InvariantCulture))
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil">PeHeaderUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetTimeStamp">GetTimeStamp Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework Namespace</a><br />