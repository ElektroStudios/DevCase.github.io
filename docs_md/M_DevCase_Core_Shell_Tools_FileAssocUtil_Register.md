# FileAssocUtil.Register Method 
 

Registers or modifies a file extension in the current system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Register(
	RegistryScope scope,
	string extensionName,
	string keyReferenceName,
	string friendlyName = "",
	string defaultIcon = "%WINDIR%\System32\shell32.dll",
	int iconIndex = 0,
	string executable = "%WINDIR%\System32\OpenWith.exe",
	string arguments = ""%1""
)
```

**VB**<br />
``` VB
Public Shared Sub Register ( 
	scope As RegistryScope,
	extensionName As String,
	keyReferenceName As String,
	Optional friendlyName As String = "",
	Optional defaultIcon As String = "%WINDIR%\System32\shell32.dll",
	Optional iconIndex As Integer = 0,
	Optional executable As String = "%WINDIR%\System32\OpenWith.exe",
	Optional arguments As String = ""%1""
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim extensionName As String
Dim keyReferenceName As String
Dim friendlyName As String
Dim defaultIcon As String
Dim iconIndex As Integer
Dim executable As String
Dim arguments As StringFileAssocUtil.Register(scope, extensionName, 
	keyReferenceName, friendlyName, 
	defaultIcon, iconIndex, executable, 
	arguments)
```

**C++**<br />
``` C++
public:
static void Register(
	RegistryScope scope, 
	String^ extensionName, 
	String^ keyReferenceName, 
	String^ friendlyName = L"", 
	String^ defaultIcon = L"%WINDIR%\System32\shell32.dll", 
	int iconIndex = 0, 
	String^ executable = L"%WINDIR%\System32\OpenWith.exe", 
	String^ arguments = L""%1""
)
```

**F#**<br />
``` F#
static member Register : 
        scope : RegistryScope * 
        extensionName : string * 
        keyReferenceName : string * 
        ?friendlyName : string * 
        ?defaultIcon : string * 
        ?iconIndex : int * 
        ?executable : string * 
        ?arguments : string 
(* Defaults:
        let _friendlyName = defaultArg friendlyName ""
        let _defaultIcon = defaultArg defaultIcon "%WINDIR%\System32\shell32.dll"
        let _iconIndex = defaultArg iconIndex 0
        let _executable = defaultArg executable "%WINDIR%\System32\OpenWith.exe"
        let _arguments = defaultArg arguments ""%1""
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope that will owns the file association.</dd><dt>extensionName</dt><dd>Type: System.String<br />The extension name (eg: .txt).</dd><dt>keyReferenceName</dt><dd>Type: System.String<br />The name of the registry key to reference.</dd><dt>friendlyName (Optional)</dt><dd>Type: System.String<br />The friendly name for this file extension (visible in Windows Esplorer).</dd><dt>defaultIcon (Optional)</dt><dd>Type: System.String<br />The icon filepath.</dd><dt>iconIndex (Optional)</dt><dd>Type: System.Int32<br />The index image of the icon resource.</dd><dt>executable (Optional)</dt><dd>Type: System.String<br />The executable path that will open the file.</dd><dt>arguments (Optional)</dt><dd>Type: System.String<br />The executable arguments, normally this value is set as '"%1"' to take the filepath as the only one argument, or '"%1" %*' to take the filepath as first argument and additional arguments.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>extensionName</td></tr><tr><td>InvalidEnumArgumentException</td><td>scope</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
FileAssoc.Register(scope:=RegistryScope.CurrentUser,
               extensionName:=".elek",
               keyReferenceName:="ElektroFile",
               friendlyName:="Elektro File",
               defaultIcon:="%WinDir%\System32\Shell32.ico",
               iconIndex:=0,
               executable:="%WinDir%\notepad.exe",
               arguments:="""%1""")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_FileAssocUtil">FileAssocUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />