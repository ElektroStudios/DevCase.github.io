# RegistryUtil.CreateValue(*T*) Method (RegistryView, String, String, String, *T*, RegistryValueKind)
 

Creates or replaces a registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreateValue<T>(
	RegistryView view,
	string rootKeyName,
	string subKeyPath,
	string valueName,
	T valueData,
	RegistryValueKind valueType = 1
)

```

**VB**<br />
``` VB
Public Shared Sub CreateValue(Of T) ( 
	view As RegistryView,
	rootKeyName As String,
	subKeyPath As String,
	valueName As String,
	valueData As T,
	Optional valueType As RegistryValueKind = 1
)
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim rootKeyName As String
Dim subKeyPath As String
Dim valueName As String
Dim valueData As T
Dim valueType As RegistryValueKindRegistryUtil.CreateValue(view, rootKeyName, 
	subKeyPath, valueName, valueData, 
	valueType)
```

**C++**<br />
``` C++
public:
generic<typename T>
static void CreateValue(
	RegistryView view, 
	String^ rootKeyName, 
	String^ subKeyPath, 
	String^ valueName, 
	T valueData, 
	RegistryValueKind valueType = 1
)
```

**F#**<br />
``` F#
static member CreateValue : 
        view : RegistryView * 
        rootKeyName : string * 
        subKeyPath : string * 
        valueName : string * 
        valueData : 'T * 
        ?valueType : RegistryValueKind 
(* Defaults:
        let _valueType = defaultArg valueType 1
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.CreateValue``1(Microsoft.Win32.RegistryView,System.String,System.String,System.String,``0,Microsoft.Win32.RegistryValueKind)"\]</dd><dt>rootKeyName</dt><dd>Type: System.String<br />The rootkey name.</dd><dt>subKeyPath</dt><dd>Type: System.String<br />The subkey path.</dd><dt>valueName</dt><dd>Type: System.String<br />The value name.</dd><dt>valueData</dt><dd>Type: *T*<br />The value data.</dd><dt>valueType (Optional)</dt><dd>Type: Microsoft.Win32.RegistryValueKind<br />The registry value type.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>rootKeyName or subKeyPath or valueName</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_CreateValue">CreateValue Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />