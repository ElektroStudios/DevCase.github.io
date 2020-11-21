# SymbolUtil.GetSymbols Method 
 

Gets the symbols of the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static List<SymbolInfo> GetSymbols(
	string filepath,
	SymOptionFlags symbolOptions = SymOptionFlags.None
)
```

**VB**<br />
``` VB
Public Shared Function GetSymbols ( 
	filepath As String,
	Optional symbolOptions As SymOptionFlags = SymOptionFlags.None
) As List(Of SymbolInfo)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim symbolOptions As SymOptionFlags
Dim returnValue As List(Of SymbolInfo)

returnValue = SymbolUtil.GetSymbols(filepath, 
	symbolOptions)
```

**C++**<br />
``` C++
public:
static List<SymbolInfo>^ GetSymbols(
	String^ filepath, 
	SymOptionFlags symbolOptions = SymOptionFlags::None
)
```

**F#**<br />
``` F#
static member GetSymbols : 
        filepath : string * 
        ?symbolOptions : SymOptionFlags 
(* Defaults:
        let _symbolOptions = defaultArg symbolOptions SymOptionFlags.None
*)
-> List<SymbolInfo> 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The .dll or .pdb filepath.</dd><dt>symbolOptions (Optional)</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SymOptionFlags">DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags</a><br />The symbol options.</dd></dl>

#### Return Value
Type: List(<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo">SymbolInfo</a>)<br />List(Of SymbolInfo).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim library As String = "C:\C++ lib.dll"

For Each symbol As SymbolInfo In GetSymbols(library)

    Dim sb As New Global.System.Text.StringBuilder
    With sb
        .AppendLine(String.Format("Address: {0}", CStr(symbol.Address)))
        .AppendLine(String.Format("Flags: {0}", symbol.Flags.ToString()))
        .AppendLine(String.Format("Index: {0}", CStr(symbol.Index)))
        .AppendLine(String.Format("Module Base Address: {0}", CStr(symbol.ModBase)))
        .AppendLine(String.Format("Name: {0}", symbol.Name))
        .AppendLine(String.Format("Size: {0}", CStr(symbol.Size)))
        .AppendLine(String.Format("Tag: {0}", symbol.Tag.ToString()))
    End With
    Debug.WriteLine(sb.ToString())

Next symbol
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_SymbolUtil">SymbolUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />