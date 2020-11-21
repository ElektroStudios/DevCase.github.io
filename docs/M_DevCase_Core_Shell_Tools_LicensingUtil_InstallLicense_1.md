# LicensingUtil.InstallLicense Method (String)
 

Installs a Windows license on the current operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void InstallLicense(
	string licFilepath
)
```

**VB**<br />
``` VB
Public Shared Sub InstallLicense ( 
	licFilepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim licFilepath As StringLicensingUtil.InstallLicense(licFilepath)
```

**C++**<br />
``` C++
public:
static void InstallLicense(
	String^ licFilepath
)
```

**F#**<br />
``` F#
static member InstallLicense : 
        licFilepath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>licFilepath</dt><dd>Type: System.String<br />The license file path.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/cc534589(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/cc534589(v=vs.85).aspx</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim licFilepath As String = "C:\License.lic"
InstallLicense(licFilepath)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_LicensingUtil">LicensingUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_LicensingUtil_InstallLicense">InstallLicense Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />