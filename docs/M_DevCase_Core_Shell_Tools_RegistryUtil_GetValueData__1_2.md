# RegistryUtil.GetValueData(*T*) Method (RegistryView, String, String, RegistryValueOptions)
 

Gets the data of a registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T GetValueData<T>(
	RegistryView view,
	string fullKeyPath,
	string valueName,
	RegistryValueOptions registryValueOptions = 0
)

```

**VB**<br />
``` VB
Public Shared Function GetValueData(Of T) ( 
	view As RegistryView,
	fullKeyPath As String,
	valueName As String,
	Optional registryValueOptions As RegistryValueOptions = 0
) As T
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim fullKeyPath As String
Dim valueName As String
Dim registryValueOptions As RegistryValueOptions
Dim returnValue As T

returnValue = RegistryUtil.GetValueData(view, 
	fullKeyPath, valueName, registryValueOptions)
```

**C++**<br />
``` C++
public:
generic<typename T>
static T GetValueData(
	RegistryView view, 
	String^ fullKeyPath, 
	String^ valueName, 
	RegistryValueOptions registryValueOptions = 0
)
```

**F#**<br />
``` F#
static member GetValueData : 
        view : RegistryView * 
        fullKeyPath : string * 
        valueName : string * 
        ?registryValueOptions : RegistryValueOptions 
(* Defaults:
        let _registryValueOptions = defaultArg registryValueOptions 0
*)
-> 'T 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.GetValueData``1(Microsoft.Win32.RegistryView,System.String,System.String,Microsoft.Win32.RegistryValueOptions)"\]</dd><dt>fullKeyPath</dt><dd>Type: System.String<br />The registry key full path.</dd><dt>valueName</dt><dd>Type: System.String<br />The value name.</dd><dt>registryValueOptions (Optional)</dt><dd>Type: Microsoft.Win32.RegistryValueOptions<br />The registry value options.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*<br />The value data.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData">GetValueData Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />