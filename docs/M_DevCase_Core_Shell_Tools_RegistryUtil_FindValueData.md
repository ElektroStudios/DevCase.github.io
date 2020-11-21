# RegistryUtil.FindValueData Method 
 

Finds on a registry path all the values that contains data that matches the specified criteria.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<RegInfo> FindValueData(
	RegistryView view,
	string rootKeyName,
	string subKeyPath,
	string valueData,
	bool matchFullData,
	bool ignoreCase,
	SearchOption searchOption
)
```

**VB**<br />
``` VB
Public Shared Function FindValueData ( 
	view As RegistryView,
	rootKeyName As String,
	subKeyPath As String,
	valueData As String,
	matchFullData As Boolean,
	ignoreCase As Boolean,
	searchOption As SearchOption
) As IEnumerable(Of RegInfo)
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim rootKeyName As String
Dim subKeyPath As String
Dim valueData As String
Dim matchFullData As Boolean
Dim ignoreCase As Boolean
Dim searchOption As SearchOption
Dim returnValue As IEnumerable(Of RegInfo)

returnValue = RegistryUtil.FindValueData(view, 
	rootKeyName, subKeyPath, valueData, 
	matchFullData, ignoreCase, searchOption)
```

**C++**<br />
``` C++
public:
static IEnumerable<RegInfo^>^ FindValueData(
	RegistryView view, 
	String^ rootKeyName, 
	String^ subKeyPath, 
	String^ valueData, 
	bool matchFullData, 
	bool ignoreCase, 
	SearchOption searchOption
)
```

**F#**<br />
``` F#
static member FindValueData : 
        view : RegistryView * 
        rootKeyName : string * 
        subKeyPath : string * 
        valueData : string * 
        matchFullData : bool * 
        ignoreCase : bool * 
        searchOption : SearchOption -> IEnumerable<RegInfo> 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.FindValueData(Microsoft.Win32.RegistryView,System.String,System.String,System.String,System.Boolean,System.Boolean,System.IO.SearchOption)"\]</dd><dt>rootKeyName</dt><dd>Type: System.String<br />The rootkey name.</dd><dt>subKeyPath</dt><dd>Type: System.String<br />The subkey path.</dd><dt>valueData</dt><dd>Type: System.String<br />The data to find.</dd><dt>matchFullData</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), matches all the data, otherwise matches a part of the data.</dd><dt>ignoreCase</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), performs a non-sensitive stringcase comparison (for String data).</dd><dt>searchOption</dt><dd>Type: System.IO.SearchOption<br />The search mode.</dd></dl>

#### Return Value
Type: IEnumerable(<a href="T_DevCase_Core_Shell_RegInfo">RegInfo</a>)<br />IEnumerable(T)

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>rootKeyName or subKeyPath or subKeyName</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />