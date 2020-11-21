# DnLibUtil.GetTypes Method (String)
 

Gets all the Types defined (including nested Types) inside a .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<TypeDef> GetTypes(
	string assemblyPath
)
```

**VB**<br />
``` VB
Public Shared Function GetTypes ( 
	assemblyPath As String
) As ReadOnlyCollection(Of TypeDef)
```

**VB Usage**<br />
``` VB Usage
Dim assemblyPath As String
Dim returnValue As ReadOnlyCollection(Of TypeDef)

returnValue = DnLibUtil.GetTypes(assemblyPath)
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<TypeDef^>^ GetTypes(
	String^ assemblyPath
)
```

**F#**<br />
``` F#
static member GetTypes : 
        assemblyPath : string -> ReadOnlyCollection<TypeDef> 

```


#### Parameters
&nbsp;<dl><dt>assemblyPath</dt><dd>Type: System.String<br />The assembly filepath.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(TypeDef)<br />A ReadOnlyCollection(T) containing the Types defined (including nested Types) inside a .NET assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim types As ReadOnlyCollection(Of TypeDef) = GetTypes("C:\Application.exe")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DnLib_DnLibUtil">DnLibUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DnLib_DnLibUtil_GetTypes">GetTypes Overload</a><br /><a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib Namespace</a><br />