# PeHeaderUtil.IsStrongNameSigned Method (String)
 

Gets a value that determine whether the specified .NET assembly is strong-name signed.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsStrongNameSigned(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function IsStrongNameSigned ( 
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Boolean

returnValue = PeHeaderUtil.IsStrongNameSigned(filepath)
```

**C++**<br />
``` C++
public:
static bool IsStrongNameSigned(
	String^ filepath
)
```

**F#**<br />
``` F#
static member IsStrongNameSigned : 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The assembly file path.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified assembly is strong-name signed; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assemblyPath As String = "C:\Assembly.exe"
Dim isStrongNameSigned As Boolean = IsStrongNameSigned(assemblyPath)

Console.WriteLine(isStrongNameSigned.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil">PeHeaderUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DotNetFramework_PeHeaderUtil_IsStrongNameSigned">IsStrongNameSigned Overload</a><br /><a href="N_DevCase_ThirdParty_DotNetFramework">DevCase.ThirdParty.DotNetFramework Namespace</a><br />