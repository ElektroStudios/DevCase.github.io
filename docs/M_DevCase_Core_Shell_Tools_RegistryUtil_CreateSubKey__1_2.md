# RegistryUtil.CreateSubKey(*T*) Method (RegistryView, String, String, RegistryKeyPermissionCheck, RegistryOptions)
 

Creates a new registry subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RegInfo<T> CreateSubKey<T>(
	RegistryView view,
	string rootKeyName,
	string subKeyPath,
	RegistryKeyPermissionCheck registryKeyPermissionCheck = 0,
	RegistryOptions registryOptions = 0
)

```

**VB**<br />
``` VB
Public Shared Function CreateSubKey(Of T) ( 
	view As RegistryView,
	rootKeyName As String,
	subKeyPath As String,
	Optional registryKeyPermissionCheck As RegistryKeyPermissionCheck = 0,
	Optional registryOptions As RegistryOptions = 0
) As RegInfo(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim rootKeyName As String
Dim subKeyPath As String
Dim registryKeyPermissionCheck As RegistryKeyPermissionCheck
Dim registryOptions As RegistryOptions
Dim returnValue As RegInfo(Of T)

returnValue = RegistryUtil.CreateSubKey(view, 
	rootKeyName, subKeyPath, registryKeyPermissionCheck, 
	registryOptions)
```

**C++**<br />
``` C++
public:
generic<typename T>
static RegInfo<T>^ CreateSubKey(
	RegistryView view, 
	String^ rootKeyName, 
	String^ subKeyPath, 
	RegistryKeyPermissionCheck registryKeyPermissionCheck = 0, 
	RegistryOptions registryOptions = 0
)
```

**F#**<br />
``` F#
static member CreateSubKey : 
        view : RegistryView * 
        rootKeyName : string * 
        subKeyPath : string * 
        ?registryKeyPermissionCheck : RegistryKeyPermissionCheck * 
        ?registryOptions : RegistryOptions 
(* Defaults:
        let _registryKeyPermissionCheck = defaultArg registryKeyPermissionCheck 0
        let _registryOptions = defaultArg registryOptions 0
*)
-> RegInfo<'T> 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.CreateSubKey``1(Microsoft.Win32.RegistryView,System.String,System.String,Microsoft.Win32.RegistryKeyPermissionCheck,Microsoft.Win32.RegistryOptions)"\]</dd><dt>rootKeyName</dt><dd>Type: System.String<br />The rootkey name.</dd><dt>subKeyPath</dt><dd>Type: System.String<br />The subkey path.</dd><dt>registryKeyPermissionCheck (Optional)</dt><dd>Type: Microsoft.Win32.RegistryKeyPermissionCheck<br />The registry key permission check.</dd><dt>registryOptions (Optional)</dt><dd>Type: Microsoft.Win32.RegistryOptions<br />The registry options.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo</a>(*T*)<br />The registry key.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>rootKeyName or subKeyPath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_CreateSubKey">CreateSubKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />