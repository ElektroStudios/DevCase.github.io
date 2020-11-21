# HostsUtil.FileCreate Method 
 

Creates the Hosts file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void FileCreate(
	bool overwrite
)
```

**VB**<br />
``` VB
Public Shared Sub FileCreate ( 
	overwrite As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim overwrite As BooleanHostsUtil.FileCreate(overwrite)
```

**C++**<br />
``` C++
public:
static void FileCreate(
	bool overwrite
)
```

**F#**<br />
``` F#
static member FileCreate : 
        overwrite : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>overwrite</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), overwrites the Hosts file.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IOException</td><td>Hosts file already exists.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_HostsUtil">HostsUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />