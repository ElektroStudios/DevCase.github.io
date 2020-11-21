# WindowsUtil.MostRecentInstalledFrameworkVersion Property 
 

Gets a value that determines which is the most recent version of the .NET Framework runtimes installed on the current machine.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Version MostRecentInstalledFrameworkVersion { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property MostRecentInstalledFrameworkVersion As Version
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Version

value = WindowsUtil.MostRecentInstalledFrameworkVersion

```

**C++**<br />
``` C++
public:
static property Version^ MostRecentInstalledFrameworkVersion {
	Version^ get ();
}
```

**F#**<br />
``` F#
static member MostRecentInstalledFrameworkVersion : Version with get

```


#### Property Value
Type: Version<br />A value that determines which is the most recent version of the .NET Framework runtimes installed on the current machine.

## Remarks
Credits to Microsoft: <a href="https://msdn.microsoft.com/en-us/library/hh925568(v=vs.110).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/hh925568(v=vs.110).aspx</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim frameworkVersion As Version = MostRecentInstalledFrameworkVersion()
Console.WriteLine(frameworkVersion.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_WindowsUtil">WindowsUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />