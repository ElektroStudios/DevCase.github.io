# LicensingUtil.InstallLicense Method (FileInfo)
 

Installs a Windows license on the current operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void InstallLicense(
	FileInfo licFile
)
```

**VB**<br />
``` VB
Public Shared Sub InstallLicense ( 
	licFile As FileInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim licFile As FileInfoLicensingUtil.InstallLicense(licFile)
```

**C++**<br />
``` C++
public:
static void InstallLicense(
	FileInfo^ licFile
)
```

**F#**<br />
``` F#
static member InstallLicense : 
        licFile : FileInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>licFile</dt><dd>Type: System.IO.FileInfo<br />The license file.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>PlatformNotSupportedException</td><td>Windows 7 or newer is required to use this feature.</td></tr><tr><td>FileNotFoundException</td><td>License file not found.</td></tr><tr><td>Exception</td><td>The Software Licensing Service determined that the license is invalid. or Unknown error occurred during the license installation attempt.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/cc534589(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/cc534589(v=vs.85).aspx</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim licFile As New FileInfo("C:\License.lic")
InstallLicense(licFile)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_LicensingUtil">LicensingUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_LicensingUtil_InstallLicense">InstallLicense Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />