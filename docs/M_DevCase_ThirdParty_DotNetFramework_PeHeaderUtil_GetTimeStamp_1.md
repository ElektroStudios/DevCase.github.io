# PeHeaderUtil.GetTimeStamp Method (String)
 

Gets the compilation timestamp of the specified .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DateTimeOffset GetTimeStamp(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetTimeStamp ( 
	filepath As String
) As DateTimeOffset
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As DateTimeOffset

returnValue = PeHeaderUtil.GetTimeStamp(filepath)
```

**C++**<br />
``` C++
public:
static DateTimeOffset GetTimeStamp(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetTimeStamp : 
        filepath : string -> DateTimeOffset 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The assembly file path.</dd></dl>

#### Return Value
Type: DateTimeOffset<br />The resulting timestamp.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assemblyPath As String = "C:\Assembly.exe"
Dim timeStamp As DateTimeOffset = GetTimeStamp(assemblyPath)

Console.WriteLine(timeStamp.ToString("dd/MMMM/yyyy HH:mm:ss", CultureInfo.InvariantCulture))
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil">PeHeaderUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_GetTimeStamp">GetTimeStamp Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework Namespace</a><br />