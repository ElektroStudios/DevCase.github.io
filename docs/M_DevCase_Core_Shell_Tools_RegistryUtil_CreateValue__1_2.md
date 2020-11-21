# RegistryUtil.CreateValue(*T*) Method (RegistryView, String, String, *T*, RegistryValueKind)
 

Creates or replaces a registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreateValue<T>(
	RegistryView view,
	string fullKeyPath,
	string valueName,
	T valueData,
	RegistryValueKind valueType = 1
)

```

**VB**<br />
``` VB
Public Shared Sub CreateValue(Of T) ( 
	view As RegistryView,
	fullKeyPath As String,
	valueName As String,
	valueData As T,
	Optional valueType As RegistryValueKind = 1
)
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim fullKeyPath As String
Dim valueName As String
Dim valueData As T
Dim valueType As RegistryValueKindRegistryUtil.CreateValue(view, fullKeyPath, 
	valueName, valueData, valueType)
```

**C++**<br />
``` C++
public:
generic<typename T>
static void CreateValue(
	RegistryView view, 
	String^ fullKeyPath, 
	String^ valueName, 
	T valueData, 
	RegistryValueKind valueType = 1
)
```

**F#**<br />
``` F#
static member CreateValue : 
        view : RegistryView * 
        fullKeyPath : string * 
        valueName : string * 
        valueData : 'T * 
        ?valueType : RegistryValueKind 
(* Defaults:
        let _valueType = defaultArg valueType 1
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.CreateValue``1(Microsoft.Win32.RegistryView,System.String,System.String,``0,Microsoft.Win32.RegistryValueKind)"\]</dd><dt>fullKeyPath</dt><dd>Type: System.String<br />The registry key full path.</dd><dt>valueName</dt><dd>Type: System.String<br />The value name.</dd><dt>valueData</dt><dd>Type: *T*<br />The value data.</dd><dt>valueType (Optional)</dt><dd>Type: Microsoft.Win32.RegistryValueKind<br />The registry value type.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_CreateValue">CreateValue Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />