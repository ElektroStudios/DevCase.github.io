# AppUtil.AddRelativeAssemblyReferencePaths Method 
 

Adds the specified directories in the private application's path, to look for referenced assemblies.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void AddRelativeAssemblyReferencePaths(
	string[] folderPaths
)
```

**VB**<br />
``` VB
Public Shared Sub AddRelativeAssemblyReferencePaths ( 
	folderPaths As String()
)
```

**VB Usage**<br />
``` VB Usage
Dim folderPaths As String()

AppUtil.AddRelativeAssemblyReferencePaths(folderPaths)
```

**C++**<br />
``` C++
public:
static void AddRelativeAssemblyReferencePaths(
	array<String^>^ folderPaths
)
```

**F#**<br />
``` F#
static member AddRelativeAssemblyReferencePaths : 
        folderPaths : string[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>folderPaths</dt><dd>Type: System.String[]<br />The registry scope.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The specified assembly reference path must be a relative directory path within the current application directory.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim assRefPaths As String() = {".\", ".\Dependencies"}
AddRelativeAssemblyReferencePaths(assRefPaths)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />