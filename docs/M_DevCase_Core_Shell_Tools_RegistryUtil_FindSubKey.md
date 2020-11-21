# RegistryUtil.FindSubKey Method (RegistryView, String, String, Boolean, Boolean, SearchOption)
 

Finds on a registry path all the subkey names that matches the specified criteria.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<RegInfo> FindSubKey(
	RegistryView view,
	string fullKeyPath,
	string subKeyName,
	bool matchFullSubKeyName,
	bool ignoreCase,
	SearchOption searchOption
)
```

**VB**<br />
``` VB
Public Shared Function FindSubKey ( 
	view As RegistryView,
	fullKeyPath As String,
	subKeyName As String,
	matchFullSubKeyName As Boolean,
	ignoreCase As Boolean,
	searchOption As SearchOption
) As IEnumerable(Of RegInfo)
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim fullKeyPath As String
Dim subKeyName As String
Dim matchFullSubKeyName As Boolean
Dim ignoreCase As Boolean
Dim searchOption As SearchOption
Dim returnValue As IEnumerable(Of RegInfo)

returnValue = RegistryUtil.FindSubKey(view, 
	fullKeyPath, subKeyName, matchFullSubKeyName, 
	ignoreCase, searchOption)
```

**C++**<br />
``` C++
public:
static IEnumerable<RegInfo^>^ FindSubKey(
	RegistryView view, 
	String^ fullKeyPath, 
	String^ subKeyName, 
	bool matchFullSubKeyName, 
	bool ignoreCase, 
	SearchOption searchOption
)
```

**F#**<br />
``` F#
static member FindSubKey : 
        view : RegistryView * 
        fullKeyPath : string * 
        subKeyName : string * 
        matchFullSubKeyName : bool * 
        ignoreCase : bool * 
        searchOption : SearchOption -> IEnumerable<RegInfo> 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.FindSubKey(Microsoft.Win32.RegistryView,System.String,System.String,System.Boolean,System.Boolean,System.IO.SearchOption)"\]</dd><dt>fullKeyPath</dt><dd>Type: System.String<br />The registry key full path.</dd><dt>subKeyName</dt><dd>Type: System.String<br />The subkey name to find.</dd><dt>matchFullSubKeyName</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), matches all the subkey name, otherwise matches a part of the name.</dd><dt>ignoreCase</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), performs a non-sensitive stringcase comparison.</dd><dt>searchOption</dt><dd>Type: System.IO.SearchOption<br />The search mode.</dd></dl>

#### Return Value
Type: IEnumerable(<a href="T_DevCase_Core_Shell_RegInfo">RegInfo</a>)<br />IEnumerable(T)

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_FindSubKey">FindSubKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />